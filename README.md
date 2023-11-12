#include<stdio.h>
void main()
{
int a,*p;
printf("Enter a number");
scanf("%d",&a);
p=&a;
printf("value of a=%d\n",*p);
printf("address of a=%p\n",p);
}
