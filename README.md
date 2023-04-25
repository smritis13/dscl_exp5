# dscl_exp5
Arrays in C
An array in C is a fixed-size collection of similar data items stored in contiguous memory locations. It can be used to store the collection of primitive data types such as int, char, float, etc., and also derived and user-defined data types such as pointers, structures, etc

![image](https://user-images.githubusercontent.com/124857385/234313210-5b5aee73-2cc6-46df-a447-4629a31b9faf.png)
![image](https://user-images.githubusercontent.com/124857385/234313271-93488747-78fc-4646-a750-2dd56168b13e.png)



	#include <stdio.h>
	int main()
	{
		// array declaration and initialization
		int arr[5] = { 10, 20, 30, 40, 50 };

		// modifying element at index 2
		arr[2] = 100;

		// traversing array using for loop
	printf("Elements in Array: ");
		for (int i = 0; i < 5; i++) {
			printf("%d ", arr[i]);
		}

		return 0;
	}
<img width="365" alt="Screenshot 2023-04-07 193043" src="https://user-images.githubusercontent.com/124857385/231528138-e1cb5c38-da44-4c99-9d9b-820529976eff.png">

