Files expected: maxProduct.c

Allowed functions: none

---

You are given an array of integers nums[] of length n (where n > 0).

The program should find and output the maximum product of any contiguous subarray within the array.

Create a C function maxProductSubarray that takes the array nums[] and its length n as input and returns the maximum product of any contiguous subarray within the array.

Implement an efficient algorithm to find the maximum product subarray.

You should NOT provide a main.

You don't have to follow the norm.

Your algorithm will be tested against the other teams.

Note: You were provided a maxProduct.o file, you can find Adrian's compiled solution there. Test with it in case of doubts.


Main examople:
```
#include <stdio.h>

int maxProductSubarray(int nums[], int n) {
    // Your implementation here
}

int main() {
    int nums[] = {2, 3, -2, 4};
    int n = sizeof(nums) / sizeof(nums[0]);
    printf("Maximum product subarray: %d\n", maxProductSubarray(nums, n));
    return 0;
}
```
Output: 6 (the subarray is {2, 3})


You are also given a tester. Compile the object file given with your file.

$> cc -c maxProduct.c -o maxProduct.o
$> cc maxProduct.o tester.o -o test

