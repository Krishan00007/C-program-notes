# *PPS Assignment*


![enter image description here](https://lh3.googleusercontent.com/vVnH6BXe-LhJsPfOsgew6B8F71aXmb7rVa7Z6HBNYyRpZ_pcReGF2OtL8iwd2MX3qC6zUX5Axfwm)
 
## ***Submitted By :***
##### ***Name : Krishan***           
##### ***Class Roll No. : 1921057***
##### ***University Roll no. : 1905355***
##### ***Branch : Information Tecnology(I.T)***
##### ***Section  : I.T. (A)***
##### ***Subject code: ESC18104/18105***


# My C programes 

## 1:Write a source code to print hello budding engineers

```
//To print  hello world
#include<stdio.h>
int main()
{                     
 printf("\nHello Budding Engineers\n");
}
```
**OUTPUT:**
``` 
 Hello Budding Engineers
```
## 2: Write a source code to fill your information and print it 

```
  // To fill your information
#include<stdio.h>

  void info();
  int main()
  {
     info();
  }

   void info()
  {  char a[20];
     int roll,age;
     long int ph;
   printf("\nEnter your information:\n");
   printf("Name = ");
    scanf("%s",a);
  printf("\nRoll no=");
scanf("%d",&roll);
printf("\nAge = ");
 scanf("%d",&age);
 printf("\nPhone no.= ");
 scanf("%ld",&ph);

printf("\nThe name is %s\nYour roll no is %d\nYour phone number is %ld\n Your age is %d\n",a,roll,ph,age);

}
```
**OUTPUT:**
```
Enter your information:
Name = Jony

Roll no=100012

Age = 25

Phone no.= 9922115566

The name is Jony
Your roll no is 100012
Your phone number is 9922115566
 Your age is 25
 ```

## 3:Write a source code to find sum of two numbers
```

     // to find sum of two numbers
     #include<stdio.h>
int main()
{                                                                                      
 int a;
 int b;
 int c ;
 printf("Enter two numbers to get sum:");
 scanf("%d  %d",&a,&b);
 printf(" \nThe result is :%d + %d= %d\n",a,b,c=a+b);
    return 0;
 }
```
**OUTPUT**:
```
Enter two numbers to get sum:45 55
 
The result is :45 + 55= 100
```
## 4:Write a source code to Sum and average of numbers
```
 // sum and average of number
#include<stdio.h>
  int main()
 {                                 
     int a,b,c,d,e,sum,avg;
                                                               
   printf("Enter five numbers:");
   scanf("%d %d %d %d %d",&a,&b,&c,&d,&e);
    sum = a+b+c+d+e;
   printf("The sum is:%d\n",sum);
   avg = sum/5;
   printf("The average is:%d\n",avg);
  }
``` 
**OUTPUT**:
```
Enter five numbers:1 2 3 4 5 
The sum is:15
The average is:3
```
  ## 5:Write a source code to find number is even or odd
  ```
       #include<stdio.h>
int main()
 {                                
    int a;   
   printf("Enter a number:");
   scanf("%d",&a);
 if(a%2==0)
  printf("The  number is even\n");
 else
   printf("The number is odd\n");
 }
```
**OUTPUT**:
```
Enter a number:4
The  number is even
```
***OR***
```
Enter a number:7
The number is odd
```
## 6:Write a source code to show the size of int,float,char,double,long,short
```
 // size of int, float, char, double, long, short
#include<stdio.h>
int main()
{                                   
 printf("Integer:%d\n",sizeof(int));
 printf("float:%d\n",sizeof(float));
 printf("character:%d\n",sizeof(char));
 printf("double:%d\n",sizeof(double));
 printf("short:%d\n",sizeof(short));
 printf("long:%d\n",sizeof(long));
 }
```
**OUTPUT**:
```
Integer:4
float:4
character:1
double:8
short:2
long:8
```
## 7:Write a source code to show area,perimeter,volume of square
```
   
 //Area,premiter,volume of square
  #include<stdio.h>
void square();
int main()
{     
 square();
 return 0;
}                                    
void square()
{
 int side;
 printf("Enter the side of square:");
 scanf("%d",&side);

 printf("\nPerimeter of square:%d",4*side);
 printf("\nArea of square:%d",side*side);
 printf("\nVolume of square:%d\n",side*side*side);
}
```
**OUTPUT**:
```
Enter the side of square:4

Perimeter of square:16
Area of square:16
Volume of square:64
```
## 8:Write a source code to show puts value upto n number using loop
```
// to show punishment using loop
 #include<stdio.h>
 int main()
 {
 int i,a;
 printf("Enter the number upto punishment is shown:");
 scanf("%d",&a);
  for(i=1;i<=a;i++)
puts("WORK HARD AND ACHIEVE SUCCESS ");
return 0;
}
```
**OUTPUT**:
```
Enter the number upto punishment is shown:10
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS
```
## 9:Write a source code to show area,diameter,circumference of circle 
```
   #include<stdio.h>
 int main()
  {
    float a;   
float  const pi=3.14;
   printf("Enter radius of circle:");
    scanf("%f\n",&a);
  printf("diameter of circle is:%f\n",2*a);
  printf("circumference of circle:%f\n",2*pi*a);
  printf("Area of circle:%f\n",pi*a*a);
return 0;
 } 
```
**OUTPUT**:
```
Enter radius of circle:6
diameter of circle is:12.000000
circumference of circle:37.680000
Area of circle:113.040001
```
## 10:Write a source code to find area and volume of rectangle
```
//find area and volume of rectangle
#include<stdio.h>
int main()
{
 int l,b,h;
 printf("Enter length of rectangle:");
 scanf("%d",&l);
 printf("\nEnter breadth of rectangle:");
 scanf("%d",&b);
 printf("\nEnter height of rectangle:");
 scanf("%d",&h);
 printf("\nThe area of rectangle is:%d",l*b);
 printf("\nThe volume is :%d\n",l*b*h);
 return 0;
 }
 ```
 **OUTPUT**:
 ```
 Enter length of rectangle:4 

Enter breadth of rectangle:3 

Enter height of rectangle:4

The area of rectangle is:12
The volume is :48
```
 
 ## 11:Write a source code to represent a table of user input 
 
 ```
  // To represent a table of user input  number
 #include<stdio.h>
 int main()
 {
    int i,j,k;
  printf("Table of:");
  scanf("%d",&j);

   for(i=0;i<=10;i++)
   printf("%d x %d = %d\n",j,i,j*i);

return 0;
}
```
**OUTPUT**:
```Table of:15
15 x 0 = 0
15 x 1 = 15
15 x 2 = 30
15 x 3 = 45
15 x 4 = 60
15 x 5 = 75
15 x 6 = 90
15 x 7 = 105
15 x 8 = 120
15 x 9 = 135
15 x 10 = 150
```
## 12:Write a source code to convert Fahrenheit to Celsius
```
//to convert fahrenhite to celcius
#include<stdio.h>
int main(){
float f,c; 
printf("Enter temp in fahrenhite :");
scanf("%f",&f);
c=((f-32)*5)/9;
printf("The celsius value is:%f\n",c);

return 0;
}
```
**OUTPUT**:
```
Enter temp in fahrehnite :450
The celsius value is:232.222229
```
## 13: Write a source code to show the table range 
```
//To show a range of table upto user input
#include<stdio.h>
int main()
{
 int a,b,n;
 printf("\n enter the starting value of table range:");
 scanf("%d",&b);
 printf("\n enter the last value of table range:");
 scanf("%d",&n);
 for(b;b<=n;b++)
{
 printf("\n");
 for(a=0;a<=10;a++)
{
 printf("%d x %d = %d\n",b,a,b*a);

}
}
 return 0;
 }
```
**OUTPUT**:
```
enter the starting value of table range:2

 enter the last value of table range:4

2 x 0 = 0
2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
2 x 4 = 8
2 x 5 = 10
2 x 6 = 12
2 x 7 = 14
2 x 8 = 16
2 x 9 = 18
2 x 10 = 20

3 x 0 = 0
3 x 1 = 3
3 x 2 = 6
3 x 3 = 9
3 x 4 = 12
3 x 5 = 15
3 x 6 = 18
3 x 7 = 21
3 x 8 = 24
3 x 9 = 27
3 x 10 = 30

4 x 0 = 0
4 x 1 = 4
4 x 2 = 8
4 x 3 = 12
4 x 4 = 16
4 x 5 = 20
4 x 6 = 24
4 x 7 = 28
4 x 8 = 32
4 x 9 = 36
4 x 10 = 40
```
## 14:Write a source code to show even table range
``` 
// To show only even table range
#include<stdio.h>
int main()
{
int m,n,a;
printf("Enter starting value of range:");
scanf("%d",&m);
printf("\nEnter ending value of range:");
scanf("%d",&n);

for(int i=m;i<=n;i++)
{
printf("\n");
 for(a=0;a<=10;a++)
{
if(i%2==0)
printf("%d X %d = %d\n",i,a,i*a);

else
 printf("  ");
}
}
return 0;
}
```
**OUTPUT**:
```
Enter starting value of range:10

Enter ending value of range:15

10 X 1 = 10                                                                  
10 X 2 = 20                                                                  
10 X 3 = 30
10 X 4 = 40
10 X 5 = 50
10 X 6 = 60
10 X 7 = 70
10 X 8 = 80
10 X 9 = 90
10 X 10 = 100

                      
12 X 0 = 0
12 X 1 = 12
12 X 2 = 24
12 X 3 = 36
12 X 4 = 48
12 X 5 = 60
12 X 6 = 72
12 X 7 = 84
12 X 8 = 96
12 X 9 = 108
12 X 10 = 120

                      
14 X 0 = 0
14 X 1 = 14
14 X 2 = 28
14 X 3 = 42
14 X 4 = 56
14 X 5 = 70
14 X 6 = 84
14 X 7 = 98
14 X 8 = 112
14 X 9 = 126
14 X 10 = 140
```
## 15: Write a source code to show result of operands
```
//To show results using operands(+,-,*,%,/)
#include<stdio.h>
int main()
{
float a,b;
 char c;
printf("enter first  number:");
scanf("%f",&a);
printf("enter operator[+ - % / *]:");
scanf(" %c",&c);
printf("enter second number:");
scanf("%f",&b);
int d,r;
d=(int) a;
r=(int) b;
switch(c)
{
case '+': printf("The result is:%.2f\n",a+b); break;
case '-':printf("The result is:%.2f\n",a-b); break;
case '*':printf("The result is:%.2f\n",a*b); break;
case '%':printf("The result is:%d\n",d%r); break;
case '/':printf("The result is:%.2f\n",a/b); break;
default : printf("Enter correct operator ");
}
return 0;
}
```

**OUTPUT**:
```
enter first  number:20
enter operator[+ - % / *]: *
enter second number:10
The result is:200.00
```
#### ***OR***
```
enter first  number:20
enter operator[+ - % / *]:+
enter second number:10
The result is:30.00
```
#### ***OR***
```
enter first  number:20
enter operator[+ - % / *]:-
enter second number:10
The result is:10.00
```
#### ***OR***
```
enter first  number:20
enter operator[+ - % / *]:/
enter second number:10
The result is:2.00
```
#### ***OR***
```
enter first  number:20
enter operator[+ - % / *]:%
enter second number:10
The result is:0
```
## 16:Write a code to call a patterns of face and calculator
```
// call a pattern of face or calculator
       #include<stdio.h>

void calculator();
void face();
int main()
{  int a;
 printf("enter 0 to see a calculator or 1 to see face\n");
 scanf("%d",&a);

if(a==0)
{
   calculator();
}
   else if(a==1)
{
     face();
  }
 else
{
  printf("enter correct values\n");
}
}
 void calculator()
{ 
puts(" _______________");
puts("|               |");
puts("|_______________|");
puts("| 1 | 2 | 3 |   |");
puts("|___|___|___|   |");
puts("| 4 | 5 | 6 | + |");
puts("|___|___|___|___|");
puts("| 7 | 8 | 9 | - |");
puts("|___|___|___|___|");
puts("|     0     | * |");
puts("|___________|___|");
}
 
 void face()
{
puts("___________________");
puts("|   XXXXXXXXXXX   |");
puts("|   ( ^     ^ )   |");
puts("|   ( 0     0 )   |");
puts("|    \\   |   /    |");
puts("|     \\     /     |");
puts("|      \\ = /      |");
puts("|       \\_/       |");
puts("|        |        |");
puts("|________|________|");
}
```
**OUTPUT**:IF YOU ENTER 0 THEN OUTPUT IS :
``` 
enter 0 to see a calculator or 1 to see face
0
 _______________
|               |
|_______________|
| 1 | 2 | 3 |   |
|___|___|___|   |
| 4 | 5 | 6 | + |
|___|___|___|___|
| 7 | 8 | 9 | - |
|___|___|___|___|
|     0     | * |
|___________|___|
```
IF YOU ENTER 1 THEN OUTPUT
```
enter 0 to see a calculator or 1 to see face
1
___________________
|   XXXXXXXXXXX   |
|   ( ^     ^ )   |
|   ( 0     0 )   |
|    \   |   /    |
|     \     /     |
|      \ = /      |
|       \_/       |
|        |        |
|________|________|
```
## 17:Write a code to convert Fahrenheit to Celsius and kelvin
```
  // To covert  fahrenheit to celsius and kelvin
                 #include<stdio.h>
 int main()
 {
  float a,b,c;
  printf("Enter a fahrenheit value:");
  scanf("%f",&a);
b=((a-32.00)*5.00)/9.00;
 printf("celsius value is:%.2f\n",b);

 printf("kelvin value is:%.2f\n",c=b+273.15);
  return 0;} 
```
**OUTPUT**:
```
Enter a fahrenheit value:450
celsius value is:232.22
kelvin value is:505.37
```

## 18:Write a code to show stars pattern
```
 // TO show stars using loop 
#include<stdio.h>
int main()
{ int i,j,k;
 printf("Enter the no. to show pattern:");
 scanf("%d",&k);
 
  for(i=k;i>=1;i--)
 {
  for(j=i;j>=1;j--)
 {
  printf("* ");
 }
 printf("\n");
 }
 return 0;
 }
 ```
 **OUTPUT**:
 ```
 Enter the no. to show pattern:8
* * * * * * * * 
* * * * * * * 
* * * * * * 
* * * * * 
* * * * 
* * * 
* * 
*
```
 
 ## 19:Write a code to show factorial result
 ```
 //To show factorial of user input
#include<stdio.h>
int main()
{
 int a,result=1;
 printf("Enter the factorial of:");
 scanf("%d",&a);
 for(int i=a;i>=1;i--)
{
printf("%d X ",i);
result=result*i;
}
printf("= %d\n",result);
return 0;
}
```
**OUTPUT**:
```
Enter the factorial of:5
5 X 4 X 3 X 2 X 1 X = 120
```
 ## 20:Write a code to show stars pattern 
 ```
 //to show star pattern for n numbers
#include<stdio.h>
int main()
{
 int i,j,k;
 printf("Enter the value upto pattern is shown:");
 scanf("%d",&k);

 for(i=1;i<=k;i++)
{
  for(j=1;j<=i;j++)
{
  printf("* ");
 }
 printf("\n");
 }
 return 0;
}
```
**OUTPUT**:
```
Enter the value upto pattern is shown:8
* 
* * 
* * * 
* * * * 
* * * * * 
* * * * * * 
* * * * * * * 
* * * * * * * * 
```

## 21:Write a code to show Matrix multiplication
 ```
#include<stdio.h>
int main()
{
int sum=0,m,n,p,q,c,d,k;
int first[10][10], second[10][10], multiply[10][10];
// for matrix 1
printf("Enter the number of rows and column of first matrix:\n");
scanf("%d %d",&m,&n);
printf("Enter elements of first matrix:\n");

for(c=0;c<m;c++)
 for(d=0;d<n;d++)
  scanf("%d",&first[c][d]);
// for second matrix
printf("Enter the number of rows and columns of second matrix:\n");
scanf("%d %d",&p,&q);

if(n!=p){
printf("matrix multipication cannot be possible !!!!\n");}

else{
printf("Enter the elements of second matrix:\n");
for(c=0;c<p;c++)
 for(d=0;d<q;d++)
  scanf("%d",&second[c][d]);

for(c=0;c<m;c++)
{
 for(d=0;d<q;d++)
{
  for(k=0;k<p;k++)
{                             
  sum = sum + first[c][k] * second[k][d];
  }
   multiply[c][d] = sum;
 sum =0;
}
}

  printf("product of the matrix:\n");
  
  for(c=0;c<m;c++)
{
  for(d=0;d<q;d++)
   printf("%d\t",multiply[c][d]);
   printf("\n");
}
}                             
 return 0;
 }
 ```
 **OUTPUT**:
 ```
 Enter the number of rows and column of first matrix:
2 2
Enter elements of first matrix:
3 4
5 6
Enter the number of rows and columns of second matrix:
2 2
Enter the elements of second matrix:
1 2
3 4
product of the matrix:
15      22
23      34
```
## 22: Write a code to show matrix addition
```
#include<stdio.h>
int main()
{
 int m,n,q,p,c,d;
 int first[100][100],second[100][100],sum[100][100];
// first matrix
printf("Enter the rows and colums of matrix:\n");
scanf("%d %d",&m,&n);
printf("Enter the elements of first matrix:\n");
 
for(c=0;c<m;c++)
 for(d=0;d<n;d++)
  scanf("%d",&first[c][d]);
// second matrix
printf("Enter the rows and colums of second matrix:\n");
scanf("%d %d",&q,&p);
if(m==q||n==p)
{
printf("Enter the elements of second matrix:\n");

for(c=0;c<q;c++)
 for(d=0;d<p;d++)
  scanf("%d",&second[c][d]);

printf("Sum of matrix is:\n");

for(c=0;c<m;c++)
{
 for(d=0;d<n;d++)
{
   sum[c][d] = first[c][d]+second[c][d];
 printf("%d\t",sum[c][d]);
}
printf("\n");
}
}
else
 printf("addition cannot possible!!!\n");

return 0;                     
}
```
**OUTPUT**
```
Enter the rows and colums of matrix:
2 3
Enter the elements of first matrix:
1 2 3
4 5 6
Enter the rows and colums of second matrix:
2 3
Enter the elements of second matrix:
1 2 3 
4 5 6
Sum of matrix is:
2       4       6
8       10      12
```
## 23: Write a source code to show number is positive or negative
```
     // To show positive or negative number  
   #include<stdio.h>
int main()
{
 int a;
 printf("enter a value :");
  scanf("%d",&a);

if(a>0)
printf("No is positive\n");

else if(a<0)
printf("No is negative\n");

else {
 printf("It is not positive or negative");
      }
return 0;
}
```
**OUTPUT**
```
enter a value :15
No is positive
```
### **OR**
```
enter a value :-16
No is negative
```
## 24: Write a source code to show number is prime or not
```
#include<stdio.h>
int main()
{
int last;
printf("enter number:");
scanf("%d",&last);
int prime;
for(int a=2;a<last;a++)
{
prime=0;
for(int i=2;i<last;i++)
{
if(last%i==0)
{
prime=prime+1;
printf("no. is not prime\n");
break;
}
}
if(prime==0)
{
printf("no. is prime\n");
break;
}
break;
}
return 0;
}
```
**OUTPUT**
```
enter number:13
no. is prime
```
#### **OR**
```
enter number:15
no. is not prime
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MDA5NDg3LC0xNjg4MzgzMjc0LC0xMj
UwMzk3NzM4LC0xMjUwMzk3NzM4LDExOTgxNTE5MzMsLTY4NTQx
MjA2MCwtODUxOTkwNDEwLDQ0NTYxMzI4OSwtMTQ3OTY1NTQ5Ni
wtODUyODE2ODg2LDE4MTg4NDY3NTEsLTEwODMwMzE0OTcsLTkx
NTkxMTYyNywtMTI0MDU2OTI3NSw0ODg3NzQ1MjgsMTkwMDc5Nz
g4Niw3MDQ0Njc2MzMsLTEyMzIyNzA1MDQsLTIwMjQwMzA3NDMs
LTE5NDEyOTE4NTBdfQ==
-->