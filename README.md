# Quick Sort Algorithm Using Hoare's Partitioning

## Introduction
Quick Sort is a highly efficient sorting algorithm that uses the divide-and-conquer strategy. It works by partitioning an array into smaller sub-arrays and then sorting each sub-array independently. This implementation utilizes Hoare's partitioning scheme, known for its efficiency and fewer swaps compared to other partitioning methods.

## Algorithm Overview

### Divide and Conquer Strategy
The divide-and-conquer strategy involves three main steps:
1. **Divide**: Split the array into two sub-arrays based on a pivot element.
2. **Conquer**: Recursively sort the two sub-arrays.
3. **Combine**: Combine the sorted sub-arrays to form the final sorted array. (In the case of Quick Sort, this step is implicit as the array is sorted in place.)

### Hoare's Partitioning
Hoare's partitioning algorithm works by selecting a pivot element and partitioning the other elements into two sub-arrays:
1. Choose the pivot element from the array (we choose the leftmost element as the pivot in this implementation).
2. Initialize two indices, `i` and `j`. `i` starts from the leftmost element and `j` starts from the rightmost element.
3. Increment `i` until an element greater than or equal to the pivot is found.
4. Decrement `j` until an element less than or equal to the pivot is found.
5. If `i` is less than `j`, swap `A[i]` and `A[j]`.
6. Repeat steps 3-5 until `i` is greater than or equal to `j`.
7. Return `j` as the partition index.

### Quick Sort
Quick Sort algorithm follows these steps:
1. If the array has one or no elements, it is already sorted.
2. Otherwise, partition the array using Hoare's partitioning method.
3. Recursively apply Quick Sort to the left and right sub-arrays.



**link**
https://youtu.be/W56M8Etq0nU


**refrences**
https://www.youtube.com/watch?v=7h1s2SojIRw

# Book
introdution to algorithm design and analysis
