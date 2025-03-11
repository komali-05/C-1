# C-1
Printing value of given index using loops
#include <stdio.h>

int main()
{
    int n,s,d,i,j=0,k=0;
    printf("enter a no.");
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        if(i%2!=0)
        {
            s=6*j;
            j++;
        }
        else if(i%2==0)
        {
            d=7*k;
            k++;
             }
           }
    if(n%2!=0)
    printf("%d\n",s);
    else
    printf("%d\n",d);
    return 0;
}
