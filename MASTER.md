#include<stdio.h>
void sum()
{
    int a,b,sum=0;
    printf("Enter the first number:");
    scanf("%d",&a);
    printf("Enter the second number:");
    scanf("%d",&b);
    sum=a+b;
    printf("The sum is: %d",sum);
}
int main()
{
    sum();
return 0;
}
