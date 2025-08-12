in c
#include <stdio.h>

int main() {
    int arr[100] = {1, 2, 3, 4};  // initial array
    int n = 4; // current size
    int element = 5;

    // Insert at the end
    arr[n] = element;
    n++; // increase size

    // Print updated array
    printf("Array after inserting: ");
    for (int i = 0; i < n; i++) {
        printf("%d ", arr[i]);
    }
    return 0;
}
in python
# Initial array
arr = [1, 2, 3, 4]

# Element to insert
element = 5

# Insert at the end
arr.append(element)

print("Array after inserting:", arr)
