# Sorting_in_C
 This repository includes every kind of implementation of sorting using C :
1. Bubble Sort :
Bubble sort is a simple sorting algorithm that repeatedly steps through the
list, compares adjacent elements, and swaps them if they are in the wrong order.
The process is repeated until the list is sorted. 
 
2. Selection sort :
Selection sort is another simple sorting algorithm. It divides the input list
into two parts: the sublist of items already sorted, which is built up from left
to right at the front (left) of the list, and the sublist of items remaining to
be sorted that occupy the rest of the list. Initially, the sorted sublist is
empty and the unsorted sublist is the entire input list. The algorithm proceeds
by finding the smallest (or largest, depending on the sorting order) element
from the unsorted sublist, swapping it with the leftmost unsorted element
(putting it in sorted order), and moving the sublist boundaries one element to
the right.

3. Quick sort :
Quick sort is an efficient sorting algorithm that uses a divide-and-conquer
approach. It works by selecting a 'pivot' element from the array and
partitioning the other elements into two sub-arrays, according to whether they
are less than or greater than the pivot. The sub-arrays are then sorted
recursively.

 4. Merge Sort :
Merge sort is a divide-and-conquer algorithm that divides the array into two
halves, recursively sorts them, and then merges the sorted halves.

5. Heap Sort :
Heap sort is a comparison-based sorting technique based on a binary heap data
structure. It's similar to selection sort where we first find the maximum
element and place the maximum element at the end. We repeat the same process for
the remaining elements.

6. Insertion Sort :
Insertion sort is a simple sorting algorithm that builds the final sorted array
one item at a time. It is much less efficient on large lists than more advanced
algorithms such as quicksort, heapsort, or merge sort. However, it has the
advantage of being simple and efficient for small data sets.

7. Here's a comparison of various sorting algorithms commonly implemented in C:

1. Bubble Sort
Algorithm: Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
Time Complexity:
Best: O(n)
Average: O(n^2)
Worst: O(n^2)
Space Complexity: O(1) (In-place)
Stability: Stable
Use Case: Simple to implement but inefficient for large datasets.
2. Selection Sort
Algorithm: Divides the input into a sorted and an unsorted region, and repeatedly selects the smallest (or largest) element from the unsorted region and moves it to the end of the sorted region.
Time Complexity:
Best: O(n^2)
Average: O(n^2)
Worst: O(n^2)
Space Complexity: O(1) (In-place)
Stability: Unstable
Use Case: Simple but not suitable for large lists.
3. Insertion Sort
Algorithm: Builds the final sorted array one item at a time, with the benefit of being efficient for small data sets and mostly sorted arrays.
Time Complexity:
Best: O(n)
Average: O(n^2)
Worst: O(n^2)
Space Complexity: O(1) (In-place)
Stability: Stable
Use Case: Efficient for small datasets or nearly sorted arrays.
4. Merge Sort
Algorithm: A divide-and-conquer algorithm that divides the array into halves, recursively sorts them, and then merges the sorted halves.
Time Complexity:
Best: O(n log n)
Average: O(n log n)
Worst: O(n log n)
Space Complexity: O(n) (Not in-place)
Stability: Stable
Use Case: Efficient and stable; good for large datasets but requires additional memory.
5. Quick Sort
Algorithm: Another divide-and-conquer algorithm that selects a pivot element and partitions the array around the pivot, recursively sorting the partitions.
Time Complexity:
Best: O(n log n)
Average: O(n log n)
Worst: O(n^2) (rare)
Space Complexity: O(log n) (In-place)
Stability: Unstable
Use Case: Generally the fastest sorting algorithm for large datasets with good average performance.
6. Heap Sort
Algorithm: Converts the array into a heap data structure, then repeatedly extracts the maximum element from the heap and reconstructs the heap.
Time Complexity:
Best: O(n log n)
Average: O(n log n)
Worst: O(n log n)
Space Complexity: O(1) (In-place)
Stability: Unstable
Use Case: Efficient and performs well with large datasets.
