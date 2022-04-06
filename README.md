# QuickSort

### Quicksort is a method for sorting an array by repeatedly partitioning it into sub-arrays by:

* Selecting an element from the current array. This element is called the pivot element, and in my implementation, I used the mid element.

* Comparing every element in the array to the pivot element, swap the elements into sides greater than and less than. The partition point in the array is where we guarantee everything before is less and everything after is greater than.

* Repeating this process on the sub-arrays separated by the partition point. Do this until a sub-array contains a single element. When the partitioning and swapping are done, the arrays are sorted from smallest to largest.

### The worst case runtime for quicksort is O(N^2) and the average runtime for quicksort is O(N logN). The worst case runtime is so unusual that the quicksort algorithm is typically referred to as O(N logN)