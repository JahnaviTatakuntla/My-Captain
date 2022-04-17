# My-Captain
//C program to swap two numbers without
       using a temporary variable

#include<stdio.h>

int main()

{

int a=10,b=20;

printf("Before swapping a=%d b=%d",a,b);

a=a+b;//a=30 (10+20)

b=a-b;//b=10 (30-20) 

a=a-b;//a=20 (30-10)

printf("\n After swapping a=%d b=%d",a,b);

return 0;

}



