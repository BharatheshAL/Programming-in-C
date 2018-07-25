#include<stdio.h>
#include<stdlib.h>
int main()
{
int a,b,c,largest;
printf(" enter the three numbers to find the largest\n);
scanf("%d%d%d\n", &a,&b,&c);
largest=(a>b)?(a>c?a:c):(b>c?b:c);   //** ternory operator **//
printf(" the largest of three numbers is %d ", largest);
return 0;
}
