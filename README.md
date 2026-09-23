# prac1-DAA-
### Summary

* **Bubble Sort:** Repeatedly compares adjacent elements and swaps them if they are in the wrong order. Simple but slow for large data.
* **Selection Sort:** Finds the smallest element and places it in the correct position. Easy to implement but takes **O(n²)** time.
* **Insertion Sort:** Builds the sorted array one element at a time. Efficient for small or nearly sorted data.
* **Merge Sort:** Divides the array into smaller parts and merges them in sorted order. It has **O(n log n)** time complexity.
* **Quick Sort:** Selects a pivot and partitions the array around it. It is generally fast, with average **O(n log n)** complexity.

### Conclusion

Sorting algorithms are important for arranging data efficiently. **Bubble, Selection, and Insertion Sort** are simple but less efficient for large datasets, while **Merge Sort and Quick Sort** are generally better for large datasets. The choice of algorithm depends on the size and nature of the data.
# PRAC-2
### Summary

* **Linear Search:** Checks each element one by one until the required element is found. It works on both sorted and unsorted data and has **O(n)** time complexity.
* **Binary Search:** Repeatedly divides a **sorted** array into two halves to find the required element. It is faster than linear search and has **O(log n)** time complexity.

### Conclusion

Linear search is simple and useful for small or unsorted data, while binary search is more efficient for large, sorted datasets. Choosing the right search algorithm improves the speed and efficiency of data retrieval.
# PRAC-3
### Summary

* **Max Heap Sort:** Uses a Max Heap where the largest element is placed at the root. It is commonly used to sort elements in **ascending order**.
* **Min Heap Sort:** Uses a Min Heap where the smallest element is placed at the root. It is commonly used to sort elements in **descending order**.
* Both algorithms have a **time complexity of O(n log n)**.

### Conclusion

Max Heap and Min Heap Sort are efficient sorting techniques based on the heap data structure. They provide consistent **O(n log n)** performance and are useful for handling large datasets efficiently.
# PRAC-4
### Summary

* **Iterative Factorial:** Calculates factorial using a loop such as `for` or `while`. It is simple and uses **O(1)** extra space.
* **Recursive Factorial:** Calculates factorial by calling the same function repeatedly until reaching the base case. It uses **O(n)** stack space.
* Both methods have a **time complexity of O(n)**.

### Conclusion

Both iterative and recursive methods can calculate factorial correctly. The iterative method is more memory-efficient, while the recursive method is simpler and demonstrates the concept of recursion.
# PRAC-5
### Summary

* **Knapsack Problem:** It is an optimization problem where we select items with given weights and values to maximize total value without exceeding the bag's capacity.
* **0/1 Knapsack:** Each item can be selected **only once**.
* **Fractional Knapsack:** Items can be divided, and the **Greedy method** can be used to get the optimal solution.
* The 0/1 Knapsack is commonly solved using **Dynamic Programming** with **O(nW)** time complexity.

### Conclusion

The Knapsack algorithm helps in making the best selection under a given capacity constraint. It is widely used in resource allocation, budgeting, and optimization problems.
# PRAC-7
### Summary

* **Coin Change using Dynamic Programming:** Finds the minimum number of coins needed to make a given amount.
* It breaks the problem into smaller subproblems and stores previously calculated results to avoid repeated calculations.
* The algorithm works efficiently for different coin denominations and target amounts.
* For `n` coin types and amount `W`, the typical time complexity is **O(nW)**.

### Conclusion

The Coin Change algorithm using Dynamic Programming provides an efficient way to solve the minimum coin problem. It reduces repeated calculations and is useful in currency systems and other optimization problems.


# PRAC-8
###Summary
A graph is a data structure made up of vertices (nodes) and edges (connections). In Python, a graph can be implemented using a dictionary or an adjacency list.

BFS (Breadth-First Search) visits nodes level by level and uses a queue.

DFS (Depth-First Search) visits nodes by going as deep as possible and uses recursion or a stack.

Both BFS and DFS are commonly used for graph traversal and searching.

The time complexity of both BFS and DFS is O(V + E), where V is the number of vertices and E is the number of edges.

###Conclusion
Graph implementation provides an efficient way to represent relationships between different nodes. BFS and DFS are important algorithms for traversing and searching graphs. BFS is useful for level-wise traversal and finding shortest paths in unweighted graphs, while DFS is useful for exploring paths and solving problems such as connectivity and backtracking.



