#include<stdio.h>
#include<math.h>
#include<stdlib.h>
int main()
{
 int y;
 float x;
 
 scanf("%d",&y);
 scanf("%f",&x);
 
 
 if((y%5)==0 && (y+0.5)<=x)
 {

 
 x=x-((y)+0.5);
 printf("%.2f",x);
 
 }
 else
 {
 
 printf("%.2f",x);
 }
 return(0);
 }
