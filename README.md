#include<stdio.h>

int main(){ int n; scanf("%d",&n); for(int i=2;i<=n;i++){ if(n%i!=0) continue; else break;

								}

		if(i==n)
			printf("m是素数\n");
		else
			printf("m不是素数\n");

		return 0;

		}
