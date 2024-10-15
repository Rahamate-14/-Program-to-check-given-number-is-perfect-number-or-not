# -Program-to-check-given-number-is-perfect-number-or-not
#include<stdio.h>
void main()
{
int i,n,s=0;
printf("enter the value i");
scanf("%d",&i);
for(n=1;i>n;n++)
{
if(i%n==0)
s=s+n;
}
if(i==s)
printf("perfect number");
else
printf("not a perfect number");
}
