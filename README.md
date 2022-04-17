# My-Captain

#include <stdio.h>

int main() 
{
 int choice;
 printf("1.pizza-🍕\n 2.Burger-🍔\n 3.Pasta-🍝\n 4.French fries-🍟\n 5.Sandwich-🥪\n");
 printf("Enter your choice");
 scanf("%d",&choice);

 switch(choice)
 {
   case 1:
   printf("Food item:Pizza-🍕/n Price:Rs 239");
   break;
   
   case 2:
   printf("Food item:Burger-🍔\n Price:Rs 129");
   break;
   
   case 3:
   printf("Food item:Pasta-🍝\n Price:Rs 179");
   break;
   
   case 4:
   printf("Food item:French fries-🍟\n Price:Rs 99");
   break;
   
   case 5:
   printf("Food item:Sandwich-🍔\n Price:Rs 149");
   break;
  
   default:
   printf("invalid choice");
   break;
 }
 
}
