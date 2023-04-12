<img width="365" alt="Screenshot 2023-04-07 193043" src="https://user-images.githubusercontent.com/124857385/231528138-e1cb5c38-da44-4c99-9d9b-820529976eff.png">
# dscl_exp5
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
