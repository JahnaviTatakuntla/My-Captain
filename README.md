# My-Captain

#include <stdio.h>
int main() 
{
   int n,col,row;
   printf("Enter the number of rows: ");
   scanf("%d", &row);
for (row = 0; row < n; row++) 

    {

        for (col = 0;col <=row; col++) 

        {

            if (((row + col) % 2) == 0) 

                printf("0");

            else

                printf("1");

        

        }

        printf("\n");

    }   
}
