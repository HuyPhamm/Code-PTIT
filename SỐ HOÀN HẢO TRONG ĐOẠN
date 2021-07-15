#include<stdio.h>
int main()
{
    int n,m;
    scanf("%d %d",&n,&m);
    if(n>m)
	{
		int temp=n;
		n=m;
		m=temp;
	}
	for(int i=n;i<=m;i++)
    {
		int s=0;
		for(int j=1;j<=i/2;j++)
		{
			if(i%j==0) 
    			s+=j;
    	}
    	if(s==i)
    		printf("%d ",i);
    }
}
