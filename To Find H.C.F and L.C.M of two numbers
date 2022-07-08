#include <stdio.h>
#include <stdlib.h>
int max(int*a,int*b)
{
    if(*a>*b)
    {
        return *a;
    }
    else
    {
     return *b;
    }
}
int min(int*a,int*b)
{
    if(*a<*b)
    {
        return *a;
    }
    else
    {
     return *b;
    }
}
int main()
{
    int a,b,y,x;
    printf("Enter two numbers:");
    scanf("%d %d",&a,&b);
    y=a*b;
    printf("L.C.M of these two numbers is:");
    int ans=max(&a,&b);
    int and=min(&a,&b);
    if(ans%and==0)
    {
      x=ans;
    }
    else
    {
        x=ans*and;
    }
    printf("%d",x);
    printf("\n");
    printf("H.C.F of two numbers is:");
    printf("%d",y/x);
    return 0;
}
