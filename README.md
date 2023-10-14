# Perfect_number
#include<stdio.h>
void main()
{

    int n,I,count=0;
    printf("Enter any number ");
    scanf("%d",&n);

    for(int I=1; I<n; I++)
    {
        if(n%I==0)
        {
            printf("facters =%d\n ",I);
            count+=I;
        }
    }

    printf("sum=%d\n",count);

    if(count==n)
    {
        printf("Given number is perfect number");
    }

    else
        printf("Given number is not perfect number");
}
