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

#include<stdio.h>
int main()
{
 puts("Hello World");
 return 0;
}
##  Output of the program
Hello World 

----

## 2. Program to find Sum
----

#include<stdio.h>
int main()
{ 
     float x,y,z;

     printf("Enter The First Number: ");
     scanf("%f", &x);
     printf("\nEnter The Second Number: ");
     scanf("%f", &y);
     z = x+y;
     printf("\nAnswer is: = %.3f", z);
     return 0;
}
## Output of the program
Enter The First Number: 45.26

Enter The Second Number: 78.2648

Answer is: = 123.525
## 3. Program to print a Table
----

#include<stdio.h>
int main()
{
     float x;
     int n;

     printf("\nEnter The Table: ");
     scanf("%f",&x);

     printf("\nEnter No. Times: ");
     scanf("%d",&n);

     for(int y=1; y<=n; y++)
     {
     printf("\n%.1f x %d = %.2f",x,y,x*y);
     }
     return 0;
}
## Output of the program
----

73.0 x 1 = 73.00
73.0 x 2 = 146.00
73.0 x 3 = 219.00
73.0 x 4 = 292.00
73.0 x 5 = 365.00
73.0 x 6 = 438.00
73.0 x 7 = 511.00
## 4. Program to find Area, Perimeter of a Rectangle
----

#include<stdio.h>
int main()
{
     float l,b,A,P;

     printf("Enter length\n: ");
     scanf("%f",&l);

     printf("Enter Bredth\n: ");
     scanf("%f",&b);

     A = l*b;
     P = 2*(l+b);

     printf("Area: = %.3f\n",A);
     printf("Perimeter: = %.3f\n",P);

     return 0;
}
## Output of the program
Enter length: 24

Enter Breadth: 60

Area: = 1440.000

Perimeter: = 168.000
## 5. Program to find Interest
----

#include<stdio.h>
int main()
{
     float P,R,T,Interest;
     printf("\nEnter The Principal Amount: ");
     scanf("%f", &P);

     printf("\nEnter The Interest Rate: ");
     scanf("%f", &R);
    
     printf("\nEnter The Time (in months): ");
     scanf("%f", &T);

     Interest = P*T*R/100;
    
     printf("\nSimple Intesest is: = %.2f", Interest);
     return Interest;
}
## Output of the program
Enter The Principal Amount: 4000

Enter The Interest Rate: 4

Enter The Time (in months): 3

Simple Intesest is: = 480.00
## 6.Program to find Maximum 
----

#include<stdio.h>
int max(float x,float y);
int main()
{
     float x,y,z;

     printf("\nEnter The First Value: ");
     scanf("%f",&x);

     printf("\nEnter The Second Value: ");
     scanf("%f",&y);

     z = max(x,y);

     printf("\nMaximum value is: %.2f\n", z);

     return 0;
  }
     int max(float x,float y)
  {
     float result;

     if(x<y)
     result = y;
     else
     result = x;

     return result;
}
## Output of the program
Enter The First Value: 5

Enter The Second Value: 4

Maximum value is: 5.00
## 7.Program To find Minimum 
----

#include<stdio.h>
int min(float x,float y);
int main()

{
     float x,y,z;

     printf("\nEnter The First Value: ");
     scanf("%f",&x);

     printf("\nEnter The SecondValue: ");
     scanf("%f",&y);

     z = min(x,y);

     printf("\nMinimum value is: %.2f\n", z);

     return 0;
}

int min(float x,float y)
{
     float result;

     if(x<y)
     result = x;
     else
     result = y;

     return result;
}
## Output of the program
Enter The First Value: 5

Enter The SecondValue: 3

Minimum value is: 3.00
## 8.Program to use Arithmetic Operators  
----

#include<stdio.h>
int main()
{
     float x,y,a;

     printf("\nEnter The Value of x: ");
     scanf("%f",&x);

     printf("\nEnter The Value of y: ");
     scanf("%f",&y);

     a = x+y;
     printf("x + y = %.3f\n",a);
     a = x-y;
     printf("x - y = %.3f\n",a);
     a = y-x;
     printf("y - x = %.3f\n",a);
     a = x*y;
     printf("x * y = %.3f\n",a);
     a = x/y;
     printf("x/y = %.3f\n",a);
     a = y/x;
     printf("y/x = %.3f\n",a);

     return 0;
}
## Output of the program
Enter The Value of x: 45

Enter The Value of y: 31
x + y = 76.000
x - y = 14.000
y - x = -14.000
x * y = 1395.000
x/y = 1.452
y/x = 0.689
## 9. Program to use Assignment Operators
----

#include<stdio.h>
int main()
{

     float x,a;

     printf("\nEnter The Value of x: ");
     scanf("%f",&x);

     a = x;
     printf("Answer is a = x %.3f\n",a);
     a +=x; //answer is a+x
     printf("Answer is a+x = %.3f\n",a);
     a -=x; //answer is a-x
     printf("Answer is a-x = %.3f\n",a);
     a *=x; //answer is a*x
     printf("Answer is a*x = %.3f\n",a);
     a /=x; //answer is a/x
     printf("Answer is a/x= %.3f\n",a);

     return 0;
}
## Output of the program
Enter The Value of x: 45
Answer is a = x 45.000
Answer is a+x = 90.000
Answer is a-x = 45.000
Answer is a*x = 2025.000
Answer is a/x= 45.000
## 10. Program to find Average
----

#include<stdio.h>
float average();

int main()
{
     printf("\nAverage is: %.2f",average());
     return 0;
  }

     float average()
  {
     float x,y,z,s,a;

     printf("\nEnter The First Value: ");
     scanf("%f",&x);

     printf("Enter The Second Value: ");
     scanf("%f",&y);

     printf("Enter The Third Value: ");
     scanf("%f",&z);

     s = x+y+z;
     a = s/3;
     return a;
}
Output of the program
Enter The First Value: 45
Enter The Second Value: 34
Enter The Third Value: 18

Average is: 32.33
## 12. Program to find FizzBuzz od a Integer
----

#include<stdio.h>
int main()
{
     int n;
     printf("\nEnter the Interger: ");
     scanf("%d",&n);

     if(n%15==0)
     printf("\nFizzBuzz");
     else if(n%3==0)
     printf("Fizz\n");
     else if (n%5==0)
     printf("\nBuzz");
     else
     printf("\n%d",n);
     return 0;
}
## Output of the program
Enter the Interger: 171
Fizz
## 13. Program of print a Calculator using puts function 
----

#include<stdio.h>
void main()
{
     puts("\n\
      _______________\n\
     | 1 | 2 | 3 |   |\n\
     |___|___|___|   |\n\
     | 4 | 5 | 6 | + |\n\
     |___|___|___|___|\n\
     | 7 | 8 | 9 | - |\n\
     |___|___|___|___|\n\
     |     0     | * |\n\
     |___________|___|\n");
}
## Output of the program
 _______________
| 1 | 2 | 3 |   |
|___|___|___|   |
| 4 | 5 | 6 | + |
|___|___|___|___|
| 7 | 8 | 9 | - |
|___|___|___|___|
|     0     | * |
|___________|___|
## 14. Program to print a Face using puts function 
----

#include<stdio.h>
void main()
{
     puts("________________");
     puts("|   XXXXXXXXX  |");
     puts("|   ( ^   ^ )  |");
     puts("|   ( 0   0 )  |");
     puts("|    \\  |  /   |");
     puts("|     \\ = /    |");
     puts("|      \\_/     |");
     puts("|       |      |");
     puts("|_______|______|\n");
}
## Output of the program
 ______________
|   XXXXXXXXX  |
|   ( ^   ^ )  |
|   ( 0   0 )  |
|    \  |  /   |
|     \ = /    |
|      \_/     |
|       |      |
|_______|______|
## 15. Program of Multiplication of 2x2 Matrix
----

#include<stdio.h>
int main()
{
float a,b,c,d,e,f,g,h,i,j,k,l;

printf("\nSample of Ist matrix: | a=1      b=2 |\n                      | c=3      d=4 |\n\n\
Sample of 2nd matrix: | e=5      f=6 |\n                      | f=7      h=8 |\n\n");

     printf("Enter The Valve of a: ");
     scanf("%f",&a);
     printf("Enter The Valve of b: ");
     scanf("%f",&b);
     printf("Enter The Valve of c: ");
     scanf("%f",&c);
     printf("Enter The Valve of d: ");
     scanf("%f",&d);
     printf("Enter The Valve of e: ");
     scanf("%f",&e);
     printf("Enter The Valve of f: ");
     scanf("%f",&f);
     printf("Enter The Valve of g: ");
     scanf("%f",&g);
     printf("Enter The Valve of h: ");
     scanf("%f",&h); 

     i=(a*e)+(b*g);
     j=(a*f)+(b*h);
     k=(c*e)+(d*g);
     l=(c*f)+(d*h);

     printf("\nMultiplication of A,B is: | %.2f     %.2f |\n                          | %.2f     %.2f |",i,j,k,l);

     return 0;
}
## Output of the program
Sample of Ist matrix: | a=1      b=2 |
                      | c=3      d=4 |

Sample of 2nd matrix: | e=5      f=6 |
                      | f=7      h=8 |

Enter The Valve of a: 7
Enter The Valve of b: 5
Enter The Valve of c: 4
Enter The Valve of d: 0
Enter The Valve of e: 3
Enter The Valve of f: 5
Enter The Valve of g: 9
Enter The Valve of h: 1

Multiplication of A,B is: | 66.00     40.00 |
                          | 12.00     20.00 |
## 17. Program of FizzBuzz in a continues loop 
----

#include<stdio.h>
int main()
{
     int n,x;
     printf("\nEnter The Integer: ");
     scanf("%d",&n);
     printf("\n");

  {
     for(x=1;x<=n;x++)
     if(x%15==0)
     printf("FizzBuzz\n");
     else if(x%3==0)
     printf("Fizz\n");
     else if(x%5==0)
     printf("Buzz\n");
     else
     printf("%d\n",x);
  }

     return 0;
}
## Output of the program
Enter The Integer: 17

1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
## 18. Program to print a Pyramid
----

 #include<stdio.h>
 int main()
 {
 int i,j,n;
 printf("\nEnter number of Rows: ");
 scanf("%d",&n);
 printf("\n");
 
 for(i=1; i<=n; i++)
 {
     for(j=1; j<=2*n-1; j++)
     {
     if(j>=n-(i-1) && j<=n+(i-1))
     printf("*");
     else
     printf(" ");
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

#include<stdio.h>
int main()

{
int array[12]={1,5,9,7,3,82,46,23,23,5,10,3};
int size=12,flag=0,item,a;

printf("\nEnter the Value: ");
scanf("%d", &a);

for(int i=0;i<size;i++)
  {
    if(a==array[i])
      {
            flag=a;
            break;
      }
  }
  
    if(flag==a)
    printf("\nSearch is Sucessfull \n%d Element is present in the array\n",a);
    else
    printf("\nSearch is Unsucessfull \n%d Element is not present in the array\n",a);
    
    return 0;
}
## Output of the program
First Case

Enter the Value to be searched: 5

Search is Sucessfull 5 Element is present in the array
Second Case

Enter the Value to be searched: 2

Search is Unsucessfull 2 Element is not present in the array
## 20. Program of linear search with desirable values
----

#include<stdio.h>
int main()
{

int array[100],search,i,n;
printf("\nEnter the Number of elements in array: ");
scanf("%d",&n);
printf("\n");

  for(i=1;i<=n;i++)
  {  printf("Enter [%d] element: ",i);
     scanf("%d",&array[i]);  }
  
printf("\nEnter a number to search: ");
scanf("%d",&search);

   for(i=0;i<=n;i++)
   {
      if(array[i]==search)         //if element is found
      {  printf("\n%d is present at location %d\n",search,i);
         break;   }
      else if(i>=n)
      {  printf("\n%d is not present in the array\n",search);  }

   }

return 0;
}
## Output of the program
Enter the Number of elements in array: 5

Enter [1] element: 1
Enter [2] element: 2
Enter [3] element: 3
Enter [4] element: 4
Enter [5] element: 5

Enter a number to search: 8

8 is not present in the array
## 21. Program to find Prime number 
----

  #include<stdio.h>
  int main()
  { 
  int a;
  printf("\nEnter the Number: ");
  scanf("%d",&a);

   for(int x=1;x<a;x++)
   { 
     if(a%x!=0)
     {  printf("%d is a Prime Number",a);
        break;  }
     else
     {  printf("%d is not a Prime Number",a);
        break;  }
    }
  return 0;
  }
Output of the program
  Enter the Number: 7
  7 is not a Prime Number

  Enter the Number: 8
  8 is not a Prime Number
## 21. Program of Linear search for One Dimensional array
----

#include<stdio.h>
int main()

{
int array[12]={1,5,9,7,3,82,46,23,23,5,10,3};
int size=12,flag=0,item,a;

printf("\nEnter the Value: ");
scanf("%d", &a);

for(int i=0;i<size;i++)
  {
    if(a==array[i])
      {
            flag=a;
            break;
      }
  }
  
    if(flag==a)
    printf("\nSearch is Sucessfull \n%d Element is present in the array\n",a);
    else
    printf("\nSearch is Unsucessfull \n%d Element is not present in the array\n",a);
    
    return 0;
}
## Output of the program
First Case

Enter the Value to be searched: 5

Search is Sucessfull 5 Element is present in the array
Second Case

Enter the Value to be searched: 2

Search is Unsucessfull 2 Element
## 22. Program of Multiplication of 2x2 Matrix 
----

#include<stdio.h>
int main()
{
float a,b,c,d,e,f,g,h,i,j,k,l;

printf("\nSample of Ist matrix: | a=1      b=2 |\n                      | c=3      d=4 |\n\n\
Sample of 2nd matrix: | e=5      f=6 |\n                      | f=7      h=8 |\n\n");

     printf("Enter The Valve of a: ");
     scanf("%f",&a);
     printf("Enter The Valve of b: ");
     scanf("%f",&b);
     printf("Enter The Valve of c: ");
     scanf("%f",&c);
     printf("Enter The Valve of d: ");
     scanf("%f",&d);
     printf("Enter The Valve of e: ");
     scanf("%f",&e);
     printf("Enter The Valve of f: ");
     scanf("%f",&f);
     printf("Enter The Valve of g: ");
     scanf("%f",&g);
     printf("Enter The Valve of h: ");
     scanf("%f",&h); 

     i=(a*e)+(b*g);
     j=(a*f)+(b*h);
     k=(c*e)+(d*g);
     l=(c*f)+(d*h);

     printf("\nMultiplication of A,B is: | %.2f     %.2f |\n                          | %.2f     %.2f |",i,j,k,l);

     return 0;
}
## Output of the program
Sample of Ist matrix: | a=1      b=2 |
                      | c=3      d=4 |

Sample of 2nd matrix: | e=5      f=6 |
                      | f=7      h=8 |

Enter The Valve of a: 7
Enter The Valve of b: 5
Enter The Valve of c: 4
Enter The Valve of d: 0
Enter The Valve of e: 3
Enter The Valve of f: 5
Enter The Valve of g: 9
Enter The Valve of h: 1

Multiplication of A,B is: | 66.00     40.00 |
                          | 12.00     20.00 |
## 23. Program to find largest of four numbers using function.
----

#include <stdio.h>
int larg(int a,int b, int c,int d);
int main()
{
 int x,y,z,r;
 printf("Enter the numbers : ");
 scanf("%d %d %d %d",&x,&y,&z,&r);
 larg(x,y,z,r);
 return 0;
}
 
int larg(int a,int b,int c,int d)
{
 if((a>b)&&(a>c)&&(a>d))
 {
  printf("%d is largest\n",a);
 }
else if((b>a)&&(b>c)&&(b>d))
 {
  printf("%d is largest\n",b);
 }
else if((c>a)&&(c>b)&&(c>d))
 {
  printf("%d is largest\n",c);
 }
 else
 {
 printf("%d is largest\n",d);
 }
return 0;
}
Output of the program
Enter the numbers : 4 2 6 8
8 is largest
## 24. Program to swap using call by reference.
----

#include <stdio.h>
int swap(int ,int );
int main()
{
 int a,b;
 printf("Enter the two numbers : ");
 scanf("%d %d",&a,&b);
 printf("Before swaping %d %d\n",a,b);
 swap(a,b);
 return 0;
}
 
int swap(int a,int b)
{
 int *x,*y;
 x=&a;
 y=&b;
 printf("After swapping : %d %d\n",*y,*x);
 return 0;
}
Output of the program
Enter the two numbers : 8 5
Before swaping 8 5
After swapping : 5 8

                                                  **ThankYou**




























