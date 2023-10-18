# DAA-TEST-1
DAA-TEST

#QUESTION1 ANALYSIS<br>
The insertion sort algorithm works by repeatedly inserting an element into its correct position in a sorted list. The algorithm starts by comparing the first two elements in the list and swapping them if necessary. Then, the algorithm compares the third element to the elements in the sorted portion of the list and inserts it into its correct position. This process continues until all of the elements in the list have been inserted into their correct positions.<br>

**case secenarios**<br>
The best-case time complexity of insertion sort is O(n), where n is the number of elements in the list. This occurs when the list is already sorted. In this case, the algorithm only needs to iterate over the list once and no swaps are necessary.<br>

The average-case time complexity of insertion sort is O(n^2). This occurs when the list is randomly shuffled. In this case, the algorithm needs to iterate over the list n times and perform an average of n/2 swaps per iteration.<br>



The worst-case time complexity of insertion sort is O(n^2). This occurs when the list is sorted in reverse order. In this case, the algorithm needs to iterate over the list n times and perform n/2 swaps per iteration.<br>


#QUESTION 1 COMPARISION<br>

Insertion sort is a simple and efficient sorting algorithm that is well-suited for small lists and lists that are already partially sorted. It works by repeatedly inserting an element into its correct position in a sorted list. Insertion sort has a time complexity of O(n^2) in the average and worst cases, but it can be much faster in practice, especially for small lists.<br>

Bubble sort is another simple sorting algorithm, but it is very inefficient. It works by repeatedly comparing adjacent elements in a list and swapping them if they are in the wrong order. Bubble sort has a time complexity of O(n^2) in the worst case, and it is generally not recommended for any use cases.<br>

Merge sort is a more efficient sorting algorithm than insertion sort or bubble sort. It works by recursively dividing the list into smaller sublists, sorting the sublists, and then merging the sorted sublists back together. Merge sort has a time complexity of O(n log n) in the worst case, but it requires more memory than insertion sort or bubble sort.<br>

Insertion sort: Insertion sort is a good choice for small lists and lists that are already partially sorted. It is simple to implement and can be very fast in practice. However, it is not as efficient as merge sort for large lists.<br>
Bubble sort: Bubble sort is not recommended for any use cases, as it is very inefficient. It is only slightly slower than insertion sort in the average case, but it is much slower in the worst case.<br>
Merge sort: Merge sort is a good general-purpose sorting algorithm. It is more efficient than insertion sort or bubble sort for large lists, but it requires more memory.<br>

#QUESTION1 PRACTICAL SCENARIO<br>
Yes, insertion sort would be a good choice for a nearly sorted list with just a few elements out of order.<br>

Insertion sort works by repeatedly inserting an element into its correct position in a sorted list. This means that it is very efficient at moving elements a short distance. For a nearly sorted list, most of the elements will already be in their correct positions, so insertion sort will only need to move a few elements a short distance. This makes insertion sort very fast for nearly sorted lists.<br>

-----------------------------------------------------------------------<br>

#QUESTION2<br>
**Linear search** is a simple searching algorithm that works by sequentially checking each element in a list until the desired element is found or the end of the list is reached. Linear search is a very inefficient algorithm for large lists, as it has a time complexity of O(n). However, it is a good choice for small lists, as it is very simple to implement.<br>

**Binary search** is a more efficient searching algorithm than linear search, but it requires the list to be sorted. Binary search works by repeatedly dividing the list in half and comparing the desired element to the middle element. If the desired element is greater than the middle element, then the search is continued in the right half of the list. If the desired element is less than the middle element, then the search is continued in the left half of the list. This process is repeated until the desired element is found or the list is empty. Binary search has a time complexity of O(log n), which is much faster than linear search for large lists.<br>

**Merge sort** is a sorting algorithm that works by recursively dividing the list into smaller sublists, sorting the sublists, and then merging the sorted sublists back together. Merge sort has a time complexity of O(n log n) in the worst case, but it is a very stable algorithm, which means that the order of equal elements in the sorted list is preserved.<br>

**Quicksort** is a sorting algorithm that works by partitioning the list into two sublists, one containing elements that are less than or equal to a pivot element and the other containing elements that are greater than the pivot element. The two sublists are then sorted recursively. Quicksort has a time complexity of O(n log n) in the average case, but it can be slower than merge sort in the worst case. However, quicksort is often faster than merge sort in practice.<br>

QUESTION2 MAX ELEMENT<br>
**puesodocode**

``
def find_max(array):
  max = array[0]
  for element in array[1:]:
    if element > max:
      max = element
  return max
``

#QUESTION2 TIME COMPLEXITY OF ARRAY<br>
The time complexity of the find_max() function is O(n), where n is the number of elements in the array. This is because the algorithm needs to iterate over the entire array in order to find the maximum element.<br>

The space complexity of the find_max() function is O(1), since the algorithm only needs to store a single variable (max).<br>










