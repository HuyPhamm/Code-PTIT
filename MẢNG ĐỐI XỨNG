#include<stdio.h>
int main()
{
	int t;
	scanf("%d",&t);
	while(t--)
	{
		int n;
		scanf("%d",&n);
		int a[100];
		for(int i=0;i<n;i++)
		scanf("%d",&a[i]);
		int m=0;
		for(int i=0;i<n;i++)
		{
			if(a[i]!=a[n-1-i])
			m++;
		}
		if(m==0)
			printf("YES\n");
		else
			printf("NO\n");
	}
}
