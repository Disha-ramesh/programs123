#include <stdio.h>


int main()
{
    int n;
    
    printf("enter the number\n");
    scanf("%d",&n);

    
    printf("the digits are %d\n",n);
    while(n>0)
    {
        int x=n%10;
        printf("%d\n",x);
        n=n/10;
    }
    return 0;
    
}
