# c
This is a project for C


```c
#include<stdio.h>

int main() {
	/*
		This is
		a file to print 
		numbers
	*/

	// int a[5] = {2, 4, 5, 6, 7}; // 1D Array : array of integers

	// Array of arrays
	int b[4][3] = { {2, 1, 3}, {1, 4, 5}, {6, 7, 8}, {7, 4, -1}}; // 2d array OR Matrix

	// b[0][0] => 2, 

	// 00, 01, 02
	// 10, 11, 12
	// 20, 21, 22
	// 30, 31, 32

/*
	2 1 3


*/
	// b[1][2] => 5

	// a[0] = 2
	// a[1] = 4
	// a[2] = 5
	// ...
	// ...
	// a[4] = 7

	// for(int i = 0; i < 5; i++) {
	// 	printf("%d", a[i]);
	// 	printf("Hello");
	// }

	for(int i = 0; i < 4; i++) 
	{
		for(int j = 0; j < 3; j +=1 ) // j++ => j += 1
		{
			printf("%d\t", b[i][j]);
		}
		printf("\n");
	}

	return 0;
}
```