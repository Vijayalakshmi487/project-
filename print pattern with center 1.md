#include<stdio.h>
int main()
{
    int i,j;
    for(i=0;i<3;i++)
    {
        for(j=0;j<3;j++)
        {
            if(i==1 && j==1)
            {
                printf("1");
            }
            else
                printf("3");
        }
        printf("\n");
    }
    
    return 0;
    
}
