The most important sorting algorithms and their complexities

1. Bubble Sort is the simplest sorting algorithm 
that works by repeatedly swapping the adjacent elements 
if they are in the wrong order.
Time Complexity: O(N^2)
Auxiliary Space: O(1)

2. Selection sort is a simple and efficient sorting algorithm 
that works by repeatedly selecting the smallest (or largest) 
element from the unsorted portion of the list 
and moving it to the sorted portion of the list.
Time Complexity: O(N^2)
Auxiliary Space: O(1)

3. Insertion sort is a simple sorting algorithm 
that works similar to the way you sort playing cards in your hands. 
The array is virtually split into a sorted and an unsorted part. 
Values from the unsorted part are picked and placed at the correct 
position in the sorted part.
Time Complexity: O(N^2) 
Auxiliary Space: O(1)

4. Merge sort is defined as a sorting algorithm 
that works by dividing an array into smaller subarrays, 
sorting each subarray, and then merging the 
sorted subarrays back together to form the final sorted array.
Time Complexity: O(N log(N))
Auxiliary Space: O(N)

5. QuickSort is a sorting algorithm based on the 
Divide and Conquer algorithm that picks an element 
as a pivot and partitions the given array around the picked pivot 
by placing the pivot in its correct position in the sorted array.
Time Complexity:
Best-Average Case: O(N log (N))
Worst Case: O(N2)
Auxiliary Space: O(1)

6. Heap sort is a comparison-based sorting technique 
based on Binary Heap data structure. 
It is similar to the selection sort where we first find 
the minimum element and place the minimum element at the beginning. 
Repeat the same process for the remaining elements.
Time Complexity: O(N log N)
Auxiliary Space: O(log n)