# PROGRAMMING FOR PROGRAM SOLVING ESC-18105
## NAME-MANJOT SINGH SRAN
----

## ROLL NO-1915048
----

## BRANCH-COMPUTER SCIENCE AND ENGINEERING
## SECTION-CS(A2)
## Submitted to : Prof Hardeep Singh

## 1.Program to print Hello World
----
#include <stdio.h>
int main() {
      printf("Hello, World!");
   return 0;
}
##  Output of the program
Hello, World!

----

## 2. Program to find Sum
----
#include <stdio.h>
int main() {    

    int number1, number2, sum;
    
    printf("Enter two integers: ");
    scanf("%d %d", &number1, &number2);

    // calculating sum
    sum = number1 + number2;      
    
    printf("%d + %d = %d", number1, number2, sum);
    return 0;
}
## Output of the program
Enter The First Number: 45

Enter The Second Number: 78

Answer is: = 123
## 3. Program to print a Table
---- 
#include <stdio.h>
int main() {
    int n, i;
    printf("Enter an integer: ");
    scanf("%d", &n);
    for (i = 1; i <= 10; ++i) {
        printf("%d * %d = %d \n", n, i, n * i);
    }
    return 0;
}

## Output of the program
----
Enter an integer: 9
9 * 1 = 9
9 * 2 = 18
9 * 3 = 27
9 * 4 = 36
9 * 5 = 45
9 * 6 = 54
9 * 7 = 63
9 * 8 = 72
9 * 9 = 81
9 * 10 = 90

## 4. Program to find Area, Perimeter of a Rectangle
----
#include <stdio.h>

int main()
{
    float length, width, perimeter;

       printf("Enter length of the rectangle: ");
    scanf("%f", &length);
    printf("Enter width of the rectangle: ");
    scanf("%f", &width);

        perimeter = 2 * (length + width);

      printf("Perimeter of rectangle = %f units ", perimeter);

    return 0;
}
## Output of the program
Enter length: 24

Enter Breadth: 60

Area: = 1440.000

Perimeter: = 168.000
## 5. Program to find Interest
----
#include <stdio.h>

int main()
{
    float principle, time, rate, SI;

    /* Input principle, rate and time */
    printf("Enter principle (amount): ");
    scanf("%f", &principle);

    printf("Enter time: ");
    scanf("%f", &time);

    printf("Enter rate: ");
    scanf("%f", &rate);

    /* Calculate simple interest */
    SI = (principle * time * rate) / 100;

    /* Print the resultant value of SI */
    printf("Simple Interest = %f", SI);

    return 0;
}

## Output of the program
Enter The Principal Amount: 4000

Enter The Interest Rate: 4

Enter The Time (in months): 3

Simple Intesest is: = 480.00
## 6.Program to find Maximum 
----
#include <stdio.h>

#define MAX_SIZE 100   // Maximum array size

int main()
{
    int arr[MAX_SIZE];
    int i, max, min, size;

    /* Input size of the array */
    printf("Enter size of the array: ");
    scanf("%d", &size);

    /* Input array elements */
    printf("Enter elements in the array: ");
    for(i=0; i<size; i++)
    {
        scanf("%d", &arr[i]);
    }


    /* Assume first element as maximum and minimum */
    max = arr[0];
    min = arr[0];

    /*
     * Find maximum and minimum in all array elements.
     */
    for(i=1; i<size; i++)
    {
        /* If current element is greater than max */
        if(arr[i] > max)
        {
            max = arr[i];
        }

        /* If current element is smaller than min */
        if(arr[i] < min)
        {
            min = arr[i];
        }
    }

    /* Print maximum and minimum element */
    printf("Maximum element = %d\n", max);
    printf("Minimum element = %d", min);

    return 0;
}

## Output of the program
Enter size of the array: 10
Enter elements in the array: -10 10 0 20 -2 50 100 20 -1 10
Maximum element = 100
Minimum element = -10
## 7.Program To find Minimum 
----
#include <stdio.h>

#define MAX_SIZE 100   // Maximum array size

int main()
{
    int arr[MAX_SIZE];
    int i, max, min, size;

    /* Input size of the array */
    printf("Enter size of the array: ");
    scanf("%d", &size);

    /* Input array elements */
    printf("Enter elements in the array: ");
    for(i=0; i<size; i++)
    {
        scanf("%d", &arr[i]);
    }


    /* Assume first element as maximum and minimum */
    max = arr[0];
    min = arr[0];

    /*
     * Find maximum and minimum in all array elements.
     */
    for(i=1; i<size; i++)
    {
        /* If current element is greater than max */
        if(arr[i] > max)
        {
            max = arr[i];
        }

        /* If current element is smaller than min */
        if(arr[i] < min)
        {
            min = arr[i];
        }
    }

    /* Print maximum and minimum element */
    printf("Maximum element = %d\n", max);
    printf("Minimum element = %d", min);

    return 0;
}


## Output of the program
Enter size of the array: 10
Enter elements in the array: -10 10 0 20 -2 50 100 20 -1 10
Maximum element = 100
Minimum element = -10

## 8.Program to use Arithmetic Operators  
----
#include <stdio.h>

int main()
{
    int num1, num2;
    int sum, sub, mult, mod;
    float div;

    /*
     * Input two numbers from user
     */
    printf("Enter any two numbers: ");
    scanf("%d%d", &num1, &num2);

    /*
     * Perform all arithmetic operations
     */ 
    sum = num1 + num2;
    sub = num1 - num2;
    mult = num1 * num2;
    div = (float)num1 / num2;
    mod = num1 % num2;

    /*
     * Print result of all arithmetic operations
     */
    printf("SUM = %d\n", sum);
    printf("DIFFERENCE = %d\n", sub);
    printf("PRODUCT = %d\n", mult);
    printf("QUOTIENT = %f\n", div);
    printf("MODULUS = %d", mod);

    return 0; 
}


## Output of the program
Enter any two numbers : 20 10
SUM = 30
DIFFERENCE = 10
PRODUCT = 200
QUOTIENT = 2.000000
MODULUS = 0
## 9. Program to use Assignment Operators
----
int main()
{
    int a = 5, c;

    c = a;      // c is 5
    printf("c = %d\n", c);
    c += a;     // c is 10 
    printf("c = %d\n", c);
    c -= a;     // c is 5
    printf("c = %d\n", c);
    c *= a;     // c is 25
    printf("c = %d\n", c);
    c /= a;     // c is 5
    printf("c = %d\n", c);
    c %= a;     // c = 0
    printf("c = %d\n", c);

    return 0;
}

## Output of the program
c = 5 
c = 10 
c = 5 
c = 25 
c = 5 
c = 0
## 10. Program to find Average
----
#include <stdio.h>
int main()
{
    int num1, num2;
    float avg;

    printf("Enter first number: ");
    scanf("%d",&num1);
    printf("Enter second number: ");
    scanf("%d",&num2);

    avg= (float)(num1+num2)/2;

    //%.2f is used for displaying output upto two decimal places
    printf("Average of %d and %d is: %.2f",num1,num2,avg);

    return 0;
}
Output of the program
Enter first number: 12
Enter second number: 13
Average of 12 and 13 is: 12.50

## 12. Program to find FizzBuzz od a Integer
----
#include <stdio.h>

int main(void)
{
    int i;
    for(i=1; i<=100; i++)
    {
        if(((i%3)||(i%5))== 0)
            printf("number= %d FizzBuzz\n", i);
        else if((i%3)==0)
            printf("number= %d Fizz\n", i);
        else if((i%5)==0)
            printf("number= %d Buzz\n", i);
        else
            printf("number= %d\n",i);

    }

    return 0;
}
## Output of the program
Enter the Interger: 171
Fizz
## 13. Program of print a Calculator
----
#include <stdio.h>
int main() {
    char operator;
    double first, second;
    printf("Enter an operator (+, -, *,): ");
    scanf("%c", &operator);
    printf("Enter two operands: ");
    scanf("%lf %lf", &first, &second);

    switch (operator) {
    case '+':
        printf("%.1lf + %.1lf = %.1lf", first, second, first + second);
        break;
    case '-':
        printf("%.1lf - %.1lf = %.1lf", first, second, first - second);
        break;
    case '*':
        printf("%.1lf * %.1lf = %.1lf", first, second, first * second);
        break;
    case '/':
        printf("%.1lf / %.1lf = %.1lf", first, second, first / second);
        break;
        // operator doesn't match any case constant
    default:
        printf("Error! operator is not correct");
    }

    return 0;
}
## Output
Enter an operator (+, -, *,): *
Enter two operands: 1.5
4.5
1.5 * 4.5 = 6.8


## 14. SUM OF TWO NUMBERS
 ----
#include<stdio.h>
 
int main() {
   int a, b, sum;
 
   printf("\nEnter two no: ");
   scanf("%d %d", &a, &b);
 
   sum = a + b;
 
   printf("Sum : %d", sum);
 
   return(0);
}
## output 
Enter two no: 5 6
Sum : 11
## 15. Program of Multiplication of 3x3 Matrix
----
#include <stdio.h>
 
int main()
{
  int m, n, p, q, c, d, k, sum = 0;
  int first[10][10], second[10][10], multiply[10][10];
 
  printf("Enter number of rows and columns of first matrix\n");
  scanf("%d%d", &m, &n);
  printf("Enter elements of first matrix\n");
 
  for (c = 0; c < m; c++)
    for (d = 0; d < n; d++)
      scanf("%d", &first[c][d]);
 
  printf("Enter number of rows and columns of second matrix\n");
  scanf("%d%d", &p, &q);
 
  if (n != p)
    printf("The multiplication isn't possible.\n");
  else
  {
    printf("Enter elements of second matrix\n");
 
    for (c = 0; c < p; c++)
      for (d = 0; d < q; d++)
        scanf("%d", &second[c][d]);
 
    for (c = 0; c < m; c++) {
      for (d = 0; d < q; d++) {
        for (k = 0; k < p; k++) {
          sum = sum + first[c][k]*second[k][d];
        }
 
        multiply[c][d] = sum;
        sum = 0;
      }
    }
 
    printf("Product of the matrices:\n");
 
    for (c = 0; c < m; c++) {
      for (d = 0; d < q; d++)
        printf("%d\t", multiply[c][d]);
 
      printf("\n");
    }
  }
 
  return 0;
}
## output 
Enter number of Rows of matrix a: 3 
Enter number of Cols of matrix a: 3 

Enter elements of matrix a: 
Enter element [1,1] : 1 
Enter element [1,2] : 2 
Enter element [1,3] : 3 
Enter element [2,1] : 4 
Enter element [2,2] : 5 
Enter element [2,3] : 6 
Enter element [3,1] : 7 
Enter element [3,2] : 8 
Enter element [3,3] : 9 

Enter number of Rows of matrix b: 3 
Enter number of Cols of matrix b: 3 

Enter elements of matrix b: 
Enter element [1,1] : 1 
Enter element [1,2] : 1 
Enter element [1,3] : 1 
Enter element [2,1] : 2 
Enter element [2,2] : 2 
Enter element [2,3] : 2 
Enter element [3,1] : 3 
Enter element [3,2] : 3 
Enter element [3,3] : 3 

Matrix after multiplying elements (result matrix): 
14	14	14	 
32	32	32	 
50	50	50

## 17. TRANSPOSE MATRIX
----
#include<stdio.h>
int main()
{ 
        int m,n,i,j;
        printf("enter the number of rows and columns of matrix\n");
        scanf("%d%d",&m,&n);
        int a[m][n],b[m][n] ;
                printf("enter the elements of  matrix row wise\n");
                for(i=0;i<m;i++)
                {
                        for(j=0;j<n;j++)
                        {
                                scanf("%d",&a[i][j]);
                        }       
                }       
                
                for(i=0;i<m;i++)
                {
                        for(j=0;j<n;j++)
                        {
                                b[j][i]=a[i][j];
                        }       
                }       
                printf("transpose  of matrix is \n");
                for(i=0;i<m;i++)
                {
                        for(j=0;j<n;j++)
                        {
                                printf("%d ",b[i][j]);
                        }       
                        printf("\n");
                }       
}               
## Output of the program
enter the number of rows and columns of matrix
3
3
enter the elements of  matrix row wise
1
6
4
5
3
2
8
9
7
transpose  of matrix is 
1 5 8 
6 3 9 
4 2 7 
## 18. Program to print a Pyramid
----
#include <stdio.h>
int main() {
    int i, space, rows, k = 0;
    printf("Enter number of rows: ");
    scanf("%d", &rows);

    for (i = 1; i <= rows; ++i, k = 0) {
        for (space = 1; space <= rows - i; ++space) {
            printf("  ");
        }
        while (k != 2 * i - 1) {
            printf("* ");
            ++k;
        }
        printf("\n");
    }

    return 0;
}
## Output of the program
 Enter number of Rows: 3
 
      *  
     ***    
    *****   
   *******  
  ********* 
 ***********
## 19. Program of Linear search for One Dimensional array 
----
#include <stdio.h>
void main()
{
    int a[10], i, item;
    printf("\nEnter SEVEN elements of an array:\n");
    for (i=0; i<=6; i++)
        scanf("%d", &a[i]);
    printf("\nEnter item to search: ");
    scanf("%d", &item);
    for (i=0; i<=9; i++)
        if (item == a[i])
        {
            printf("\nItem found at location %d", i+1);
            break;
        }
    if (i > 9)
        printf("\nItem does not exist.");
    getch();
}
## Output of the program
Enter SEVEN elements of an array:
12 25 45 89 54 68 88
Enter item to search: 89
Item found at location 4
## 20. CHECK PALINDROME NUMBER
----
#include <stdio.h>
int main() {
    int n, reversedN = 0, remainder, originalN;
    printf("Enter an integer: ");
    scanf("%d", &n);
    originalN = n;

    // reversed integer is stored in reversedN
    while (n != 0) {
        remainder = n % 10;
        reversedN = reversedN * 10 + remainder;
        n /= 10;
    }

    // palindrome if orignalN and reversedN are equal
    if (originalN == reversedN)
        printf("%d is a palindrome.", originalN);
    else
        printf("%d is not a palindrome.", originalN);

    return 0;
}

## Output of the program
Enter an integer: 1001
1001 is a palindrome.
## 21. Program to find Prime number 
----
#include <stdio.h>
int main() {
    int n, i, flag = 0;
    printf("Enter a positive integer: ");
    scanf("%d", &n);

    for (i = 2; i < n / 2; ++i) {

        // condition for non-prime
        if (n % i == 0) {
            flag = 1;
            break;
        }
    }

    if (n == 1) {
        printf("1 is neither prime nor composite.");
    }
    else {
        if (flag == 0)
            printf("%d is a prime number.", n);
        else
            printf("%d is not a prime number.", n);
    }

    return 0;
}
  ## Output of the program
Enter a positive integer: 29
29 is a prime number.

  ## 22. CALL BY VALUE ----
#include <stdio.h>
 
/* function declaration */
void swap(int x, int y);
 
int main () {

   /* local variable definition */
   int a = 100;
   int b = 200;
 
   printf("Before swap, value of a : %d\n", a );
   printf("Before swap, value of b : %d\n", b );
 
   /* calling a function to swap the values */
   swap(a, b);
 
   printf("After swap, value of a : %d\n", a );
   printf("After swap, value of b : %d\n", b );
 
   return 0;
}
## Output of the program
Before swap, value of a :100
Before swap, value of b :200
After swap, value of a :100
After swap, value of b :200
 
## 23. CALL BY REFERENCE
----
#include 
void swapnum ( int *var1, int *var2 )
{
   int tempnum ;
   tempnum = *var1 ;
   *var1 = *var2 ;
   *var2 = tempnum ;
}
int main( )
{
   int num1 = 35, num2 = 45 ;
   printf("Before swapping:");
   printf("\nnum1 value is %d", num1);
   printf("\nnum2 value is %d", num2);

   /*calling swap function*/
   swapnum( &num1, &num2 );

   printf("\nAfter swapping:");
   printf("\nnum1 value is %d", num1);
   printf("\nnum2 value is %d", num2);
   return 0;
}

## Output of the program
Before swapping:
num1 value is 35
num2 value is 45
After swapping:
num1 value is 45
num2 value is 35
## 23. EMPLOYEE DETAILS USING STRUCTURE-----
#include <stdio.h>
#include <stdlib.h>
 
typedef struct{
 
    char name[30];
    int id;
    int salary;
 
} Employee;
 
int main()
{
    int i, n=2;
 
    Employee employees[n];
 
    //Taking each employee detail as input
 
    printf("Enter %d Employee Details \n \n",n);
    for(i=0; i<n; i++){
 
        printf("Employee %d:- \n",i+1);
        //Name
        printf("Name: ");
        scanf("%s",employees[i].name);
        //ID
        printf("Id: ");
        scanf("%d",&employees[i].id);
        //Salary
        printf("Salary: ");
        scanf("%d",&employees[i].salary);
 
        printf("\n");
    }
 
    //Displaying Employee details
 
    printf("-------------- All Employees Details ---------------\n");
 
    for(i=0; i<n; i++){
 
        printf("Name \t: ");
        printf("%s \n",employees[i].name);
 
        printf("Id \t: ");
        printf("%d \n",employees[i].id);
 
        printf("Salary \t: ");
        printf("%d \n",employees[i].salary);
 
        printf("\n");
    }
 
    return 0;
## output 
enter employee code                                                                                                                             
125                                                                                                                                             
enter employee name                                                                                                                             
Raghav                                                                                                                                          
enter employee department                                                                                                                       
electric                                                                                                                                        
enter employee salary                                                                                                                           
25000                                                                                                                                           
information about employee is                                                                                                                   
Employee code: 125                                                                                                                              
Employee name: Raghav                                                                                                                           
Employee department: electric                                                                                                                   
Employee salary: 25000.000000
 
 ## 24. SUM OF DIGITS OF A NUMBER
#include <stdio.h>

int main()
{
    int num, sum=0;

    /* Input a number from user */
    printf("Enter any number to find sum of its digit: ");
    scanf("%d", &num);

    /* Repeat till num becomes 0 */
    while(num!=0)
    {
        /* Find last digit of num and add to sum */
        sum += num % 10;

        /* Remove last digit from num */
        num = num / 10;
    }

    printf("Sum of digits = %d", sum);

    return 0;
}

Output of the program
Enter any number to find sum of its digit: 1234
Sum of digits = 10

                                                  **ThankYou**

