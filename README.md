#include<stdio.h>
int main()
{
    int n,i=1,s=0;
    printf("enter your counting number: ");
    scanf("%d",&n);
    do
    {
        s=s+i;
        i++;
    } // ami jodi printf while loop er moddhe rakhtam tahole output sa\tage by stage dito
   while(i<=n);
   // do.. while e  while শেশে দিতে হবে আর সেমিকোলন দিয়া লাগবে
    printf("%d\n",s);
    return 0;
}
