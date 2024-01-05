#include<stdio.h>
void main()
{
    int a=0,no, sum=0, digit;
    printf("enter a no:)");
    scanf("%d",&no);
    while(no!=0){
    digit=no%10;
    no/=10;
    a=digit*digit*digit;
    sum+=a;
    }
    printf(":)%d\n",sum);
}
