#include<stdio.h>
void main()
{
    int N,i,arr[100];
    printf("enter N:");
    scanf("%d",&N);
    for(i=0;i<N;i++)
    {
        scanf("%d",&arr[i]);
        
    }
    if(arr[i]<arr[i+1])
    {
         for(i=0;i<N;i++)
    {
        scanf("%d",arr[i+1]);
        
    }
    
    }
    else
    {
        i++;
    }
}
