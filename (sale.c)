#include<stdio.h>
int main()
{
	int n=0,sum=0;
	
	scanf("%d",&n);
	
	int a[n];
	for(int i=0;i<n;i++)
	{
		scanf("%d",&a[i]);
	}
	
	for(int i=0;i<n;i++)
	{
		sum += a[i];
	}
	float discount=0,getdis=0,total=0,vat=0,totalvat=0;
	
	if(n==1)
	{
		discount = 5.0;
		discount = discount/100;
		
		getdis = sum*discount;
		total = sum-getdis;
		
		vat = total*0.07;
		totalvat = total+vat;
		
		printf("%.1f",total);
	}
	else if(n==2)
	{
		discount = 15.0;
		discount = discount/100;
		
		getdis = sum*discount;
		total = sum-getdis;
		
		vat = total*0.07;
		totalvat = total+vat;
		
		printf("%.1f",total);
	}
	else if(n==3)
	{
		discount = 30.0;
		discount = discount/100;
		
		getdis = sum*discount;
		total = sum-getdis;
		
		vat = total*0.07;
		totalvat = total+vat;
		
		printf("%.1f",total);
	}
	
}
