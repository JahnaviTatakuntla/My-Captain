# My-Captain


#include <stdio.h>
#include <stdlib.h>

typedef struct{
    char name[30];
    int age;
    double salary;
    int phone;
} Employee;
 
int main()
{
    //number of employees
    int n=20;

    //array to store structure values of all employees
    Employee employees[n];
 
    //Taking each employee detail as input
    printf("Enter %d Employee Details \n \n",n);
    for(int i=0; i<n; i++){
        printf("Employee %d:- \n",i+1);

        //NAME
        printf("Name: ");
        scanf("%[^\n]s",employees[i].name);

        //AGE
        printf("age: ");
        scanf("%d",&employees[i].age);

       //PHONE NUMBER
     printf("phone no:");
     scanf("%d",&employees[i].phone);
        
        
        //SALARY
        printf("Salary: ");
        scanf("%lf",&employees[i].salary);
        char ch = getchar();
 
        printf("\n");
    }
    
    
//Displaying Employee details
    printf("-----Employees Details -----\n");
    for(int i=0; i<n; i++)
    {
     printf("Name \t");
     printf("age \t");
     printf("phone no \t");
     printf("Salary \t ");
        
 
 printf("%s \t",employees[i].name);
 printf("%d \t",employees[i].age);
 printf("%d \t",employees[i].phone);
 printf("%.2lf \t",employees[i].salary);
   
   printf("\n");
   
   }
 
    return 0;
}
