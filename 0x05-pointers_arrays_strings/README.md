# pointers and arrays
 They are used to access the value of a variable indirectly, through its memory address. Arrays are data structures that store a collection of elements of the same type. Each element in an array is accessed using its index.
In C programming, pointers and arrays are closely related. An array can be thought of as a collection of memory locations, each of which can be accessed using a pointer. The name of an array is a pointer to the first element in the array.
For example, the following code declares an array of 10 integers:

int arr[10];
​

The name of the array, `arr`, is a pointer to the first element in the array. The elements of the array can be accessed using the following syntax:

arr[0] // first element
arr[1] // second element
...
arr[9] // tenth element
​

Pointers can also be used to point to individual elements in an array. For example, the following code declares a pointer to the first element in the array:
int *ptr = &arr[0];
