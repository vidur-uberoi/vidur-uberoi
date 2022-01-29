/*	 This program reads two integer numbers from the 
	 keyboard and prints their sum.
*/
#include<stdio.h>

int main()
{
	// define variables
	int a, b, c;
	// read input numbers
	printf("Enter two numbers to add\n");
	scanf("%d%d",&a,&b);
	// add numbers
	c = a + b;
	// print result
	printf("Sum of the entered numbers = %d\n",c);
	return 0;
}
