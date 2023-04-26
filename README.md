# Selection-sort

Selection sort is a simple and efficient sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list. The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first element of the unsorted portion. This process is repeated for the remaining unsorted portion of the list until the entire list is sorted. One variation of selection sort is called “Bidirectional selection sort” which goes through the list of elements by alternating between the smallest and largest element, this way the algorithm can be faster in some cases.

![image](https://user-images.githubusercontent.com/125429608/234453516-201d7db7-0104-4552-968d-617bc212db87.png)

The algorithm maintains two subarrays in a given array.

The subarray which already sorted. 
The remaining subarray was unsorted.
In every iteration of the selection sort, the minimum element (considering ascending order) from the unsorted subarray is picked and moved to the beginning of the sorted subarray. 

After every iteration sorted subarray size increase by one and the unsorted subarray size decrease by one.

Flowchart of the Selection Sort: 

![image](https://user-images.githubusercontent.com/125429608/234453655-f3e98992-7584-43c7-b6c0-ea5108c0bef4.png)
