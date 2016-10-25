#include<stdio.h>
#include<conio.h>
int main()
{
int a;
printf("enter the number:");
scanf("%d",&a);
if(a%4)
{
printf("A is a leap year");
}
else
{
printf("A is not a leap year");
}
getch();
return 0;
}
