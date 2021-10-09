# passing-array-to-function.c
passing the value of array to function
#include<stdio.h>
#include<conio.h>

int func1(int array[])

{int i ;
for(i=0;i<12;i++)
{printf("value of %d is %d\n",i,array[i]);
}
array[2]=3567;
return 0;
}

int main(){
	
	int arr[]={34,45,54,45,54,4,4,4,4,4,4,3345,};

	func1(arr);
	printf("the value of 2 is %d",arr[2]);
}
