# CRT-CIVIL-C-PROGRAMQ
.write a code snipped the following statement the customer APSPDCL Electrical Board Electrical has a unic id and it charges from the Customer Based on their Consumed 

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




2.WRITE CODE IN THE PROGRAM TELUGU

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

