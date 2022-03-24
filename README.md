# OpenMP-program-to-demonstrate-the-use-of-for-clause.-
Write a simple OpenMP program to demonstrate the use of ‘for’ clause. - Sum of n’ array elements - Product of n’ array elements

From the given assessment was to explore the basic concepts of ‘for’ clause parallel programming by printing, summing array contents and producing product of array.

● Input is taken in main function.

● The printing of array is handled by ‘printArray’ function in the code.

● The summation of array is handled by ‘sumArray’ function in the code.

● The product of elements in array is produced by the ‘productArray’function in the code.

#pragma omp parallel:The code under this syntax cell is forked intosubprocesses which is handled by multiple threads of the processor.
#pragma omp for:This syntax is used to invoke paralellised approch to forloop.
