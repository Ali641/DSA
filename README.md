# DSA
#include<stdio.h>
#include<conio.h>
int main()
{
	int score[7]={10,11,12,13,14,15,16};
	int ans[7];
	int count,sum=0;
	float avg;
	for(count=0;count<=7;count++)
	{
		sum+=score[count];
	}
	avg=sum/7;
	printf("%d \n",sum);
	printf("%f \n",avg);
	printf("\n");
	for(count=0;count<=7;count++)
	{
		ans[7]=(score[count]-avg)*(score[count]-avg);
		printf("%d\n",ans[7]);
	}
}
