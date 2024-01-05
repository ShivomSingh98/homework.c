#include<stdio.h>
void main()
{
    int a,i,fact=0;
    printf("enter a no:-");
    scanf("%d",&a);
    if(a>0)
    {
        for(i=0;i<=a;i++)
        {
            fact=a*a-i;
        }
        printf("factorial=%d",fact);
    }
}
