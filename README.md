# Benchmark-Milestone-2-application-release-1.0

/*This prgram adds two integer values and displays the results*/
#include<stdio.h>
int main(void)
{
	//Declare variables
	int value1, value2, sum;

	//Assign values and calculate their sum
	value1 = 42;
	value2 = 27;
	sum = value1 + value2;

	//Display the result 
	printf("The sum of %i and %i is %i\n", value1, value2, sum);

	return 0;
}
