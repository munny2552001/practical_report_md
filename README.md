# PROGRAMMING FOR PROGRAM SOLVING ESC-18105
----
# NAME-MANJOT SINGH SRAN
----
ROLL NO-1915048
----
BRANCH-COMPUTER SCIENCE
----
SECTION-CS(A2)
----
Submitted to : Prof Hardeep Singh
----
#  1.Program to print Hello World
----
#include <stdio.h>
int main()
{
    printf("HELLO WORLD");
    return 0;
}

----
# Output of the program
----

Hello World
----
# 2. Program to find Sum
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

----
# **Output of the program**
----

Enter The First Number: 45.26

Enter The Second Number: 78.2648

Answer is: = 123.525
----
# 3. Program to print a Table
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

----
# Output of the program
----

73.0 x 1 = 73.00
73.0 x 2 = 146.00
73.0 x 3 = 219.00
73.0 x 4 = 292.00
73.0 x 5 = 365.00
73.0 x 6 = 438.00
73.0 x 7 = 511.00

----
# 4. Program to find Area, Perimeter of a Rectangle
----
#include <stdio.h>
int main()
{
    float l,b,A,p;
    printf("Enter length\n: ");
    scanf("%f",&l);
    printf("Enter breath\n: ");
    scanf("%f",&b);

    A = l*b;
    p = 2*(l+b);
    printf("Area: = %.3f\n",A);
     printf("Perimeter: = %.3f\n",p);

     return 0;

}

----
# Output of the program
----

Enter length: 24

Enter Breadth: 60

Area: = 1440.000
Perimeter: = 168.000

----
# 5. Program to find Interest
----
#include <stdio.h>
int main()
{
    float P,R,T,Interest;
    printf("Enter the Principal amount\n: ");
    scanf("%f", &P);
    printf("Enter the Interest rate\n: ");
    scanf("%f", &R);
    printf("Enter the time in months\n: ");
    scanf("%f", &T);
    Interest = P*R*T/100;

     printf("\nSimple Intesest is: = %.2f", Interest);
     return Interest;
     }

----
#  Output of the program
----

Enter The Principal Amount: 4000

Enter The Interest Rate: 4

Enter The Time (in months): 3

Simple Intesest is: = 480.00

----
# 6.Program to find Maximum
----
#include <stdio.h>
int main()
{
    float a,b;
    printf("Enter the value of a\n: ");
    scanf("%f", &a);
    printf("Enter the value of b\n: ");
    scanf("%f", &b);

    if(a>b){
        printf("a is Largest\n");
    }
    else
    {
        printf("B is largest\n");

    }


     return 0;

}

----
#  Output of the program
----

Enter The First Value: 5

Enter The Second Value: 4

Maximum value is: 5.00

----
# 7.Program To find Minimum
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

----
#  Output of the program
----

Enter The First Value: 5

Enter The SecondValue: 3

Minimum value is: 3.00

----
# 8.Program to use Arithmetic Operators
----
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

----
# Output of the program
----

Enter The Value of x: 45

Enter The Value of y: 31
x + y = 76.000
x - y = 14.000
y - x = -14.000
x * y = 1395.000
x/y = 1.452
y/x = 0.689

----
# 9. Program to use Assignment Operators
----
#include<stdio.h>
int main()
{

     float x,a;

     printf("\nEnter The Value of x: ");
     scanf("%f",&x);

     a = x;
     printf("Answer is a = x %.3f\n",a);
     a +=x;
     printf("Answer is a+x = %.3f\n",a);
     a -=x;
     printf("Answer is a-x = %.3f\n",a);
     a *=x;
     printf("Answer is a*x = %.3f\n",a);
     a /=x;
     printf("Answer is a/x= %.3f\n",a);

     return 0;
}

----
# Output of the program
----

Enter The Value of x: 45
Answer is a = x 45.000
Answer is a+x = 90.000
Answer is a-x = 45.000
Answer is a*x = 2025.000
Answer is a/x= 45.000

----
# 10. Program to find Average
----
#include <stdio.h>
int main()
{
     float x,y,z,s,a,average;

     printf("\nEnter The First Value: ");
     scanf("%f",&x);

     printf("Enter The Second Value: ");
     scanf("%f",&y);

     printf("Enter The Third Value: ");
     scanf("%f",&z);

     s = x+y+z;
     a = s/3;
      printf("\nAverage is: %.2f",a);
     return 0;
}

----
# Output of the program
----

Enter The First Value: 45
Enter The Second Value: 34
Enter The Third Value: 18

Average is: 32.33
----
# 11. Program to find FizzBuzz number
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

----
# Output of the program
----

Enter the Interger: 171
Fizz

----
# 12. Program of print a Calculator using puts function

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

----
# Output of the program
----

 _______________
| 1 | 2 | 3 |   |
|___|___|___|   |
| 4 | 5 | 6 | + |
|___|___|___|___|
| 7 | 8 | 9 | - |
|___|___|___|___|
|     0     | * |
|___________|___|

----
# 13. Program of Multiplication of 2x2 Matrix
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

----
# Output of the program

----

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

Multiplication of A,B is: | 66.00         40.00 |
                          | 12.00         20.00 |
                          

----
# 14.Program of FizzBuzz in a continues loop
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

----
# Output of the program
----

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

----
# 15.  PROGRAM TO CHECK WHETHER THE NUMBER IS EVEN OR ODD

----
#include <stdio.h>  
int oddeven(int num1);
int main ()
{
int s ;
printf ("Enter the integer:");
scanf ("%d",&s);
oddeven (s);
return 0;
}
int oddeven(int num1)
{
if (num1%2==0)
printf ("The number is even")
else
printf ("The number is odd:");
return 0;
}

----

# Output of the program
----
Enter the no : 45
no is odd

----
# 16. Program of Linear search for One Dimensional array
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

----
# Output of the program
----

First Case

Enter the Value to be searched: 5

Search is Sucessfull 5 Element is present in the array
Second Case

Enter the Value to be searched: 2

Search is Unsucessfull 2 Element is not present in the array

----
# 17. Program of linear search with desirable values
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

----
# Output of the program

----

Enter the Number of elements in array: 5

Enter [1] element: 1
Enter [2] element: 2
Enter [3] element: 3
Enter [4] element: 4
Enter [5] element: 5

Enter a number to search: 8

8 is not present in the array

----
# 18. PROGRAM TO FIND FACTORIAL OF A NUMBER

----
#include <stdio.h> 
void main() 
{ 
int a,n=1,i; 
printf("enter i : "); 
scanf("%d",&i); 
for(a=1;a<=i;a++) 
n=n*a; 
printf("factorial of i is %d \n",n); 
} 

----
# OUTPUT
----

enter i : 5
factorial of i is 120

----
# 19.Program to convert farenhiet to celcius
----
#include<stdio.h> 
int main() 
{ 
float f,c; 
printf(" Enter degree of farenhiet:  "); 
scanf("%f",&f); 
c=(f-32)*5/9; 
printf("The coverted value of  %f farenhiet is : %f Celsius\n",f,c); 
return 0; 
} 

----
#  Output of the program
----

Enter the magnitude of radius of circle :3
Area of the circle is 28.268999 
perimeter of  the circle is 18.846001

----
# 20. Program to find Prime number
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

----
#  Output of the program
----

 Enter the Number: 7
  7 is not a Prime Number

  Enter the Number: 8
  8 is not a Prime Number
  
----
# 21. Program to swap using call by reference.
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

----
# Output of the program
----

Enter the two numbers : 8 5
Before swaping 8 5
After swapping : 5 8

----
# 22.Program to check whether year is leap or not
----
#include<stdio.h>

int main()
{
int n; 
printf("Enter the year u want to check it for leap :");
scanf("%d",&n);
if(n%4==0)
printf("it is a leap year\n");
else
printf(" not a leap year\n");
return 0;
}

----


# Output of the program
----

Enter the year u want to check it for leap :2016 
it is a leap year

----
# 23.Program to check whether number is palindrome or not
----
#include<stdio.h>

int main()
{
int temp,n,r,ans=0;
printf("Enter the no : " );
scanf("%d",&n);
temp=n;
while(n>0)
{
r=n%10;
ans=ans*10+r;
n=n/10;
}
if(ans==temp)
printf("it is a palindrome no\n");
else
printf("it is not a palindrome no\n");
return 0;
}

----
#   Output of the program
Enter the no : 121
it is a palindrome no

----
# 24.Program to display fibonacchi series
----
#include<stdio.h>

int main()
{
int n,a=0,b=1,c,i;
printf(" Enter the  no of fibonachi terms u want to print: ");
scanf("%d",&n);
printf("%d\t%d\t",a,b);
for(i=1;i<=n-2;i++)
{
c=a+b;
printf("%d\t",c);
a=b;
b=c;
}
return 0;
}


----
# Output of the program
----

Enter the  no of fibonachi terms u want to print: 10
0       1       1       2       3       5       8       13      21      34 

----

                   
#                                       **Thank you**
