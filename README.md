# CRT-CIVIL-C-PROGRAMQ
Q.write a code snipped the following statement the customer APSPDCL Electrical Board Electrical has a unic id and it charges from the Customer Based on their Consumed 

1.Customer unit are less than 200 units per Rs:1.20  
2.Customer unit are less than 300 units per Rs. 1.50
3.Customer unit are less than 400 units per Rs.2.00
The consumed units are above 400 units per Rs:-2.00 and surcharge will be collected on 5% on the amount
The consumed units are above 500 units per Rs:2.50 and surcharge will be collected on 10% on the amount

#include <stdio.h>

int main(){
    int a;
    printf("enter no.of unit:");
    scanf("%d&a");
    if (a<=200)
{
    printf("amount=%f",a*1.20);
}
else if(a<=300)
{
    printf("amount=%f",a*1.50);
}
else if (a<=400)
{
    printf("amount=%f",a*1.80);
}
else if (a>=500)
{
    printf("amount=%f",a*2.00+15);
}
else
{
    printf("amount=%f",a*2.50+20);
}
}




Q.WRITE CODE IN THE PROGRAM TELUGU

#include <stdio.h>

int main() {
    // Write C code here
    printf("\u0c27\u0c30\u0c23\u0c3f\u0c27\u0c30\u0c4d");

    return 0;
}
name of the code is Dharanidhar


 
#include <stdio.h>

int main() {
    // Write C code here
    printf("\u0c1a\u0c30\u0c23\u0c4d");

    return 0;
}

name of the code is charan

Q.Write a code snipped in ladder if A B  and C are friends and they have different height determinr who is the tallent among them 
Case 1 ; 
Input : 158,198,168
Output ;-198 is tallent

Case 2 ;-
Input:-258,118,178
Output:-258 tallest


#include <stdio.h> 
void main() {
int a, b, c;
printf("Height of 3 persons:\n");
scanf("%d %d %d", &a, &b, &c);
if (a > b)
{
if (a > c)
{
printf("%d is tallest", a);
}
else 
{
printf("%d is tallest", c);
}
}
else
{
if (b > c)
{
printf("%d is tallest", b);
}
else
{
printf("%d is tallest", c);
}
}
}

Q.in a class room all the students and the teacher are playing number game if a student selesct randomly a number below 7(from 0 to 6) thev class teacher will the day of the week that corresponding to that number (sunday,monday,....,saturday)
case1:-1
input:-5
output:-friday
case2:-
input:-0
output:-sunday

#include <stdio.h>

int main() {
    int number;
    scanf("%d", &number);
    
    switch (number) {
        case 0:
            printf("It is Sunday\n");
            break;
        case 1:
            printf("It is Monday\n");
            break;
        case 2:
            printf("It is Tuesday\n");
            break;
        case 3:
            printf("It is Wednesday\n");
            break;
        case 4:
            printf("It is Thursday\n");
            break;
        case 5:
            printf("It is Friday\n");
            break;
        case 6:
            printf("It is Saturday\n");
            break;
        default:
            printf("Invalid number. Give numbers 0 to 6.\n");
    }
    return 0;
}

Q.Write a code snipped for the following statement
"In the classroom the teacher asked the student to call  out the event at the even number up to a given number and asked another student to count them
#include <stdio.h>

int main() {
    // Write C code here
    int num,count=0,i;  //variables declaration 
    scanf("%d",&num); // getting input from user at run time 
    for(i=2;i<=num;i=i+2)
    {
        printf("%d\t",1);
        count=count+1;
    }
printf("\ncount=%d,count");
return 0;
}



Q.Write a code snipped for the following statement
In the VII Lesson the techer asked one student to call out the number up to given number and asked another student to count them.

#include <stdio.h>

int main() {
    // Write C code here
    int num,total=0,i;  //variables declaration 
    scanf("%d",&num); // getting input from user at run time 
    for(i=1;i<=num;i=i+1)
    {
      total=total+i;
    }
printf("%d",total);
return 0;
}

Q.write a code snipped for the following statement 
“Syam was one of the good student in the class. He enjoyed writing on the blackboard
Whenever his teacher asked if the techer gave him a number and asked him to write a mathematical expression for it he happily wrote it on the board

#include <stdio.h>

int main() {
    // Write C code here
    int num,i; //variables declaration 
    scanf("%d",&num); // getting input from user at run time 
    for(i=1;i<=10;i=i+1)
    {
      printf("\n%d*%d=%d",num,i,num*i);
      
    }
      
      
      
      return 0;
}


Q.write a code snipped  following statement 
A Perfect number is a positive integer that is equal to its properpositive divisors (excluding the number itself)

#include <stdio.h>

int main() {
    // Write C code here
    int num,i,sum=0; //variables declaration 
    scanf("%d",&num); // getting input from user at run time 
    for(i=1;i<=num;i=i+1)
    {
     if(num%i==0)
      printf("%d",is a perfect number",num);
       }
      else
      {
      printf("%d",is not a perfect number",num);
      }
      return 0;
}


Q.the factorial loop of a non-negative integer is the product of all positive integers.Less than or equal to that integers.

#include <stdio.h>
int main() {
    int num, i, fact = 1;           // Add missing semicolon
    scanf("%d", &num);
    i = 1;                          // Initialize i
    while (i <= num) {
        fact = fact * i;            // Fix multiplication and use i instead of 1
        i++;                        // Increment i so the loop finishes
    }
    printf("%d", fact);
    return 0;                       // Place return inside main
}

Q. write a code snipped for the following statement 
A palindrome number is a number that reads the same forward and back ward 

#include <stdio.h>
int main()
{
    int n,num,sum=0,rem;
    scanf("%d",&n);
    num=n;
    while(n>0)
    {
        rem=n%10;
        sum=sum*10+rem;
        n=n/10;
    }
    if(sum==num)
    {
        printf("%d is a palindrome",num);
    }
    else
    {
        printf("%d is not a palindrome",num);
    }
    return 0;}

Q.write a code snipped for the following statement
.a strong number is apositive integer where the sum of the factorial of its individual digits equals the original number. for example, 145 is a strong number because1!
4!+5!=1+24+120=145

#include <stdio.h>
int main()
{
    int n, num, sum = 0, rem, fact, i;
    scanf("%d", &n);
    num = n;
    while (n > 0)
    {
        rem = n % 10;
        fact = 1;
        i = 1;
        while (i <= rem)
        {
            fact = fact * i;
            i++;
        }
        sum = sum + fact;
        n = n / 10;
    }
    if (sum == num)
    {
        printf("%d is a strong number", num);
    }
    else
    {
        printf("%d is not a strong number", num);
    }
    return 0;
}

Q.write a code snipped for the following statement
An Armstrong number is a number is anumber that is equal to the sum of its own dights, each raised to the power of the total number of digit
#include <stdio.h>
int main() {
    int i = 1;
    do {
        printf("%d\n", i);
        i++;
    } while (i <= 5);
    return 0;
}

Q.write a code snipped for the following statement
break statement in c is a control statement used to terminate the execution o the nearest enclosing loop [for,while or do while] or switch when a break statement is encounted 
The program immediately    

#include <stdio.h>

int main() {
    for(int i=1;i<=10;i++)
    {
        if(i==5)
        {
            break;//exit the loop when i is 5
        }
        printf("%d",i);
    }
    printf("\nloop treminated.\n");

    return 0;
}
Q. adding Function 
 
#include <stdio.h>

int sum(int a, int b)
{
    return a + b;
}

int main() {
    int x, y, add = 0;
    printf("Enter two numbers: ");
    scanf("%d%d", &x, &y);
    add = sum(x, y);
    printf("sum is %d\n", add);
    return 0;
}
  
Q. subtraction program 

#include <stdio.h>

int sum(int a, int b)
{
    return a - b;
}

int main() {
    int x, y, sub = 0;
    printf("Enter two numbers: ");
    scanf("%d%d", &x, &y);
    sub = sum(x, y);
    printf("sum is %d\n", sub);
    return 0;
}

Q.Adding and subtraction funtion
#include <stdio.h>

int sum(int a, int b)
{
    return a + b; // Correction: sum function should add, not subtract
}

int sub(int m, int n)
{
    return m - n; // Correction: sub function subtracts
}

int main() {
    int x, y, add = 0, subtra = 0; // Correction: Added '=' and fixed variable name

    printf("Enter two numbers for addition: ");
    scanf("%d%d", &x, &y);
    add = sum(x, y);
    printf("Sum is %d\n", add);

    printf("Enter two numbers for subtraction: ");
    scanf("%d%d", &x, &y);
    subtra = sub(x, y);
    printf("Subtraction is %d\n", subtra);

    return 0;
} 
