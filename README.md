#include<stdio.h>

int main()
{
    int i,n,factorial=1;
    
    printf("Enter a number:\n");
    
    scanf("%d",&n);

    for(i=2;i<=n;i++)
    
    {
        factorial=factorial*i;
        
    }
    
    printf("Factorial=%d",factorial);
    
    return 0;
    
}
