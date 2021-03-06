https://www.hackerrank.com/challenges/c-tutorial-functions
Functions:

Problem:

Functions are a bunch of statements glued together. A function is provided with zero or more arguments, and it executes the statements on it. Based on the return type, it either returns nothing (void) or something.


A sample syntax for a function is:


return_type function_name(arg_type_1 arg_1, arg_type_2 arg_2, ...) {
	...
	...
	...
	[if return_type is non void]
		return something of the type 'return_type';
}

For example, a function to read four variables and return the sum of them can be written as

int sum_of_four(int a, int b, int c, int d){
	int sum = 0;
	sum+= a;
	sum+= b;
	sum+= c;
	sum+= d;
	return int_sum;
}

You have to write a function in_max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.

Input Format:
	
	Input will contain four integers - a,b,c,d. One in each line.

Output Format:

	Print the greatest of the four integers.
	P.S: I/O will be automatically handeled.


Sample Input:
	
	3
	4
	6
	5

Sample Output:

	6


