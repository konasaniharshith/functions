# functions
programing
#include<stdio.h>  
int main()    
{    
int n,sum=0,m;    
printf("Input number:");    
scanf("%d",&n);    
while(n>0)    
{    
m=n%10;    
sum=sum+m;    
n=n/10;    
}    
printf("Sum of digits: %d",sum);    
return 0;  
}   
