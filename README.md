# Benchmark-Milestone-2-application-release-1.0



/*Basic C code Structure. This prgram adds two integer values and displays the results*/
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

/*Use of input and output*/
#include <stdio.h>

int main(void)
{

    int       integerVar = 100; //input 
    float     floatingVar = 4; //input 
    double    doubleVar = 28; //input
    char      charVar = '8'; //input 

    _Bool     boolVar = 7; //input


    printf("integerVar = %i\n", integerVar); //output
    printf("floatingVar = %f\n", floatingVar); //output
    printf("doubleVar = %e\n", doubleVar); //output
    printf("doubleVar = %g\n", doubleVar); //output
    printf("charVar = %c\n", charVar); //output


    printf("boolVar = %i\n", boolVar); //output


    return 0;

}

/*Use of variables and data types*/
// Illustrate the use of various

#include <stdio.h>

int main(void)
{
    int a = 103;
    int b = 3;
    int c = 27;
    int d = 5;
    int result;

    result = a - b;       // subtraction
    printf("a - b = %i\n", result);

    result = b * c;       // multiplication
    printf("b * c = %i\n", result);

    result = a / c;       // division
    printf("a / c = %i\n", result);

    result = a + b * c;   // precedence
    printf("a + b * c = %i\n", result);

    printf("a * b + c * d = %i\n", a * b + c * d);

    return 0;
}
/*Use of preprocessor*/
/*use of #if, #else, #elif, and #endif */

#include<stdio.h>
#include<conio.h>

#define JAY 98 // Grade number to get end results of grade level

int main()
{
#if JAY>=75
	printf("Your Mark is greater than 75\n");
	printf("You have got the grade A\n");

#elif JAY>=50 
	print("Your Mark is greater than 50 and less than 75\n");
	print("You have got the grade B\n");

#else 
	print("Your marks are less\n");
	printf("You have got the grade C\n);



#endif


return 0;
}

/*Use of loop and decision*/
#include <stdio.h>

int main()
{

	int i; //initialization
	for (i = 0; i < 10; i++) //display items less than 10
	{
		printf("%d\n", i);
	}


	return 0;


          
}

