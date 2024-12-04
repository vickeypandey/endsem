
#include<stdio.h>

int main()
{
	int low,high,mid,n,i,a;
	printf("enter no of elements: ");
	scanf("%d", &n);
	int A[n];
	printf("ENTER NO OF ELEMENTS IN SORTED MANNER");
	for(int i=0;i<n;i++)
	{
		scanf("%d",&A[i]);
	}
	printf("enter the value to find : i.e the key: ");
	scanf("%d",&a);
	low=0;
	high=n-1;
	mid=(low+high)/2;
	while(low<=high)
	{
		if(A[mid]<a)
		{
		low=mid+1;	
		}
		else if(A[mid]==a)
		{
		printf("%d found at position %d",a,mid+1);
		break;
		}
		else
		{
			high=mid-1;
		}
		mid=(low+high)/2;
	}
	if(low>high)
	{
		printf("not found");
	}
	return 0;
	}
