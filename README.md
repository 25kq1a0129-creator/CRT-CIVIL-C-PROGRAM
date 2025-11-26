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
    printf("u0c27\u0c30\u0c23\u0c3f\u0c27,u0c30,u0c4d");

    return 0;
}
name of the code is Dharanidhar


 
#include <stdio.h>

int main() {
    // Write C code here
    printf("\u0c1a\uoc30\u0c23\u0c4d");

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

Q.in a class room all the students and the teacher

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
      sum=sum+i;
    }
      
      
      
      return 0;
}
