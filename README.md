#include<stdio.h>
int main()
{
    int arr[]={1,2,3,5,4,4,3,2};
    int len =  sizeof(arr)/sizeof(arr[0]);
    for(int i=0;i<len;i++)
    {
        for(int j=i+1;j<len;j++)
        {
            if(arr[i]==arr[j])
            {
                printf("%d\n", arr[i]);
            }

        }
    }
    return 0;
}
