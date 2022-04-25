# My-Captain

#include<stdio.h>
int main()
{
  int arr1[3][3];
  int *b;
  b=&arr1;
  int i,j, rows,columns,sum=0;
  printf("\n Read a 2D-array of size 3x3 and print the matrix :\n");
     
/* Stored values into the array*/
      
 printf("Input elements in the matrix :\n");
  for(i=0;i<3;i++)
  {
      for(j=0;j<3;j++)
      {
	      printf("element is [%d][%d] : ",i,j);
	      scanf("%d",&arr1[i][j]);
      }
  }  
 
 printf("\nThe matrix is : \n");
  for(i=0;i<3;i++)
  {
      printf("\n");
      for(j=0;j<3;j++)
           printf("%d\t",arr1[i][j]);
  }
 printf("\n");

/*code for sum of the diagonal elements of the matrix */

printf("\n Please Enter Number of rows and columns : "); 	
scanf("%d %d", &i, &j);	
printf("\n Please Enter the Matrix Elements \n"); 	
for(rows = 0; rows < i; rows++) 	
{ 		
for(columns = 0;columns < j;columns++) 
	{ 		
scanf("%d", &arr1[rows][columns]); 	
} 
	} 	 	
for(rows = 0; rows < i; rows++) 
{ 		
sum = sum + arr1[rows][rows]; 
} 	

printf("\n The sum of diagonal elements of the matrix = %d",sum);
return 0;
}
