# Sortings

The arrangement of data in a preferred order is called sorting. It can be done in ascending and descending order. <br/>By sorting data, it is easier to search through it quickly and easily. The simplest example of sorting is a dictionary.

# Implementation

### Bubble Sort
Sorting takes place by stepping through all the elements one-by-one and comparing it with the adjacent element and swapping them if required.
* Worst complexity: n^2
* Average complexity: n^2
* Best complexity: n
* Space complexity: 1
* Method: Exchanging
* Class: Comparison

### Selection Sort
The smallest element is selected from the unsorted array and swapped with the leftmost element, and that element becomes a part of the sorted array. This process continues moving unsorted array boundary by one element to the right.
* Worst complexity: n^2
* Average complexity: n^2
* Best complexity: n^2
* Space complexity: 1
* Method: Selection
* Class: Comparison

### Insertion Sort
An insertion sort compares values in turn, starting with the second value in the list. If this value is greater than the value to the left of it, no changes are made. Otherwise this value is repeatedly moved left until it meets a value that is less than it. The sort process then starts again with the next value.
* Worst complexity: n^2
* Average complexity: n^2
* Best complexity: n
* Space complexity: 1
* Method: Insertion
* Class: Comparison

### Shell Sort
Shell sort is an algorithm that first sorts the elements far apart from each other and successively reduces the interval between the elements to be sorted. It is a generalized version of insertion sort.
* Worst complexity: Depends on gap sequence
* Average complexity: n*log(n)^2 or n^(3/2)
* Best complexity: n
* Method: Insertion
* Class: Comparison

### Quick Sort
Quicksort is a divide-and-conquer algorithm. It works by selecting a 'pivot' element from the array and partitioning the other elements into two sub-arrays, according to whether they are less than or greater than the pivot. The sub-arrays are then sorted recursively.
* Worst complexity: n^2
* Average complexity: n*log(n)
* Best complexity: n*log(n)
* Method: Partitioning
* Class: Comparison sort

### Radix Sort
In radix sort algorithm, a list of integer numbers will be sorted based on the digits of individual numbers. Sorting is performed from least significant digit to the most significant digit.
* Worst complexity: n*k/d
* Average complexity: n*k/d
* Space complexity: n+2^d
* Class: Non-comparison sort

### Merge Sort
Merge sort repeatedly breaks down a list into several sublists until each sublist consists of a single element and merging those sublists in a manner that results into a sorted list.
* Worst complexity: n*log(n)
* Average complexity: n*log(n)
* Best complexity: n*log(n)
* Space complexity: n
* Method: Merging

### Heap Sort
Heap sort is a comparison based sorting technique based on Binary Heap data structure. It is similar to selection sort where we first find the minimum element and place the minimum element at the beginning. We repeat the same process for the remaining elements.
* Worst complexity: n*log(n)
* Average complexity: n*log(n)
* Best complexity: n*log(n)
* Space complexity: 1
* Method: Selection
