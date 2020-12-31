#include<include.h>
#define N 10
int main()
{
				  int a[N],i,j,t;
  printf（"Please input %d ge numbers\n",N）;
  for(i=0;i<N;i++)
  {
    for(j=i+1;j<N;j++)
      if(a[i]<a[j])
        {
           t=a[i];
           a[i]=a[j];
           a[j]=t;
        }
  }
  printf("排序后的数组:\n");
  for(i=0;i<N;i++)
  printf("%d",a[i]);
  return 0;
  }
