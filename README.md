n以内的阶乘
#include<stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	int fact=1;
	int i;
	for(i=1;i<=n;i++)
	{
		fact *=i;
	}
	printf("%d\n",fact);

	return 0;
}
