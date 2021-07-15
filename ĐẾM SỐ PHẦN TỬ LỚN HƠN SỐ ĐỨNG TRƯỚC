#include<stdio.h>

int main()
{
	int t;
	scanf("%d", &t);
	while(t--)
	{
		int n;
		scanf("%d", &n);
		unsigned long long a[n+5];
		int i;
		for(i = 1; i<=n; i++) 
		scanf("%llu", &a[i]);
		int count = 1;
		int j;
		for(i = 2; i<=n; i++)
		{
			for(j = 1; j<i; j++)
			{
				if(a[j]>a[i]) 
					break;
				if(j==i-1&&a[j]<=a[i]) 
				count+=1;
			}
		}
		printf("%d", count);
		printf("\n");
	}
}
