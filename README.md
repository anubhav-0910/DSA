# Data Structures and Algorithms (DSA) Patterns

## 1. Fast and Slow Pointer
**Description**: This technique uses two pointers moving at different speeds to solve problems involving cycles, such as finding the middle of a list, detecting loops, or checking for palindromes.

- [Cycle Detection: Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/)
- [Cycle in Array: Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)
- [Palindrome in Linked List: Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)



## 2. Merge Intervals
**Description**: Intervals are often manipulated through sorting and merging based on their start and end times. This pattern efficiently handles overlapping intervals.

- [Basic Merge: Merge Intervals](https://leetcode.com/problems/merge-intervals/)
- [Interval Insertion: Insert Interval](https://leetcode.com/problems/insert-interval/)
- [Non-overlapping Intervals: Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/)



## 3. Sliding Window
**Description**: A sliding window is a subarray or substring that moves over data to solve problems efficiently in linear time.

- [Fixed Window: Maximum Sum Subarray of Size K](https://leetcode.com/problems/maximum-average-subarray-i/)
- [Variable Window: Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- [Minimum Window Substring: Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)



## 4. Islands (Matrix Traversal)
**Description**: This pattern is useful for exploring connected components in a matrix, typically using DFS or BFS to detect islands or regions.

- [Number of Islands: Number of Islands](https://leetcode.com/problems/number-of-islands/)
- [Max Area of Island: Max Area of Island](https://leetcode.com/problems/max-area-of-island/)
- [Surrounded Regions: Surrounded Regions](https://leetcode.com/problems/surrounded-regions/)



## 5. Two Pointers
**Description**: The two pointers technique involves having two different indices move through the input at different speeds to solve various array or linked list problems.

- [Pair Sum: Two Sum II - Input Array is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
- [Dutch National Flag: Sort Colors](https://leetcode.com/problems/sort-colors/)
- [Remove Duplicates: Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)



## 6. Cyclic Sort
**Description**: Cyclic sort is an efficient approach to solve problems where numbers are consecutively ordered and must be placed in the correct index.

- [Find Missing Numbers: Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/)
- [Find the Duplicate Number: Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)
- [Missing Number: Missing Number](https://leetcode.com/problems/missing-number/)



## 7. In-place Reversal of Linked List
**Description**: Reversing a linked list in place without using extra space is key for problems that require in-place list manipulations.

- [Reverse a Linked List: Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)
- [Reverse Nodes in k-Group: Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/)
- [Swap Nodes in Pairs: Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/)



## 8. Breadth First Search (BFS)
**Description**: BFS explores nodes level by level using a queue. It is particularly useful for shortest path problems.

- [Level Order Traversal: Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)
- [Shortest Path in Binary Matrix: Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/)
- [Word Ladder: Word Ladder](https://leetcode.com/problems/word-ladder/)



## 9. Depth First Search (DFS)
**Description**: DFS explores as far as possible along a branch before backtracking. It’s useful for graph traversal, pathfinding, and connected components.

- [Binary Tree Paths: Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/)
- [Path Sum: Path Sum II](https://leetcode.com/problems/path-sum-ii/)
- [Graph Traversal: Course Schedule](https://leetcode.com/problems/course-schedule/)



## 10. Two Heaps
**Description**: This pattern uses two heaps (max heap and min heap) to solve problems involving tracking medians and efficiently managing dynamic data.

- [Find Median from Data Stream: Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)
- [Sliding Window Median: Sliding Window Median](https://leetcode.com/problems/sliding-window-median/)
- [IPO: IPO](https://leetcode.com/problems/ipo/)



## 11. Subsets
**Description**: The subsets pattern generates all possible subsets (or permutations) of a given set using recursion or backtracking.

- [Generate All Subsets: Subsets](https://leetcode.com/problems/subsets/)
- [Subsets with Duplicates: Subsets II](https://leetcode.com/problems/subsets-ii/)
- [Permutations: Permutations](https://leetcode.com/problems/permutations/)



## 12. Modified Binary Search
**Description**: A modified version of binary search that applies to rotated arrays, unsorted arrays, or specialized conditions.

- [Search in Rotated Array: Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)
- [Find Minimum in Rotated Array: Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)
- [Peak Element: Find Peak Element](https://leetcode.com/problems/find-peak-element/)



## 13. Bitwise XOR
**Description**: XOR is a powerful bitwise operator that can solve problems like finding single numbers or efficiently pairing elements.

- [Single Number: Single Number](https://leetcode.com/problems/single-number/)
- [Find the Duplicate: Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)
- [Missing Number: Missing Number](https://leetcode.com/problems/missing-number/)



## 14. Top 'K' Elements
**Description**: This pattern uses heaps or quickselect to efficiently find the top 'K' largest/smallest elements from a dataset.

- [Top K Frequent Elements: Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)
- [Kth Largest Element: Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/)
- [K Closest Points: K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/)



## 15. K-way Merge
**Description**: The K-way merge technique uses a heap to efficiently merge multiple sorted lists or arrays.

- [Merge K Sorted Lists: Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)
- [Smallest Range: Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/)
- [Find K Pairs with Smallest Sums: Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/)



## 16. 0/1 Knapsack (Dynamic Programming)
**Description**: Solve optimization problems like selecting items with the maximum value under a given weight limit.

- [Knapsack Problem: Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)
- [Knapsack with Repetition: Coin Change](https://leetcode.com/problems/coin-change/)



## 17. Unbounded Knapsack (Dynamic Programming)
**Description**: Similar to the 0/1 knapsack, but items can be chosen multiple times.

- [Coin Change II: Coin Change II](https://leetcode.com/problems/coin-change-ii/)
- [Minimum Cost for Tickets: Minimum Cost For Tickets](https://leetcode.com/problems/minimum-cost-for-tickets/)



## 18. Topological Sort
**Description**: Topological sorting is useful for tasks that require dependency resolution in directed acyclic graphs (DAGs).

- [Course Schedule: Course Schedule](https://leetcode.com/problems/course-schedule/)
- [Alien Dictionary: Alien Dictionary](https://leetcode.com/problems/alien-dictionary/)
- [Course Schedule II: Course Schedule II](https://leetcode.com/problems/course-schedule-ii/)



## 19. Monotonic Stack
**Description**: A monotonic stack helps solve range queries by maintaining a stack of elements in increasing or decreasing order.

- [Next Greater Element: Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/)
- [Daily Temperatures: Daily Temperatures](https://leetcode.com/problems/daily-temperatures/)
- [Largest Rectangle in Histogram: Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)


## 20. Backtracking
**Description**: Backtracking helps in problems where you need to explore all potential solutions, such as solving puzzles, generating combinations, or finding paths.

- [N-Queens: N-Queens](https://leetcode.com/problems/n-queens/)
- [Word Search: Word Search](https://leetcode.com/problems/word-search/)
- [Combination Sum: Combination Sum](https://leetcode.com/problems/combination-sum/)


## 21. Union Find
**Description**: Union-Find (Disjoint Set) is an efficient data structure for solving problems related to connected components.

- [Graph Connectivity: Number of Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/)
- [Accounts Merge: Accounts Merge](https://leetcode.com/problems/accounts-merge/)
- [Friend Circles: Friend Circles](https://leetcode.com/problems/friend-circles/)


## 22. Greedy Algorithm
**Description**: Greedy algorithms make locally optimal choices with the hope of finding the global optimum.

- [Activity Selection: Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/)
- [Jump Game II: Jump Game II](https://leetcode.com/problems/jump-game-ii/)
- [Candy: Candy](https://leetcode.com/problems/candy/)

------
------

# Some Useful DSA Patterns Articles on LeetCode

### Two Pointers
- [Solved all Two Pointers problems in 100 days](https://leetcode.com/discuss/study-guide/1688903/Solved-all-two-pointers-problems-in-100-days)

### Sliding Window
- [Sliding Window Technique and Question Bank](https://leetcode.com/discuss/study-guide/1773891/Sliding-Window-Technique-and-Question-Bank)

### Greedy
- [Greedy for Beginners: Problems & Sample Solutions](https://leetcode.com/discuss/general-discussion/669996/greedy-for-beginners-problems-sample-solutions)

### Linked List
- [Must-Do LinkedList Problems on LeetCode](https://sarthak-acoustic.medium.com/must-do-linkedlist-problems-on-leetcode-19f47dc88fff)

### Trees
- [Tree Question Pattern | 2021 Placement](https://leetcode.com/discuss/study-guide/1337373/Tree-question-pattern-oror2021-placement)


### Binary Search

- [5 Variations of Binary Search](https://leetcode.com/discuss/interview-question/1322500/5-variations-of-Binary-search-(A-Self-Note))
- [Binary Search for Beginners: Problems & Patterns](https://leetcode.com/discuss/general-discussion/691825/Binary-Search-for-Beginners-Problems-or-Patterns-or-Sample-solutions)


### Dynamic Programming (DP)

- [Solved all Dynamic Programming (DP) problems topic-wise](https://leetcode.com/discuss/study-guide/1000929/solved-all-dynamic-programming-dp-problems-in-7-months)
- [DP for Beginners: Problems & Patterns](https://leetcode.com/discuss/general-discussion/662866/DP-for-Beginners-Problems-or-Patterns-or-Sample-Solutions)
- [Dynamic Programming Patterns based on Intuition](https://leetcode.com/discuss/general-discussion/458695/Dynamic-Programming-Patterns)


### Graphs

- [Graph for Beginners: Problems & Pattern Decoded](https://leetcode.com/discuss/general-discussion/655708/graph-for-beginners-problems-pattern-sample-solutions/)
- [Graph Algorithms: Curated Problems with Code](https://leetcode.com/discuss/study-guide/1326900/graph-algorithms-problems-to-practice)


### Bit Manipulation

- [Bit Manipulation Theory](https://leetcode.com/problems/sum-of-two-integers/solutions/84278/A-summary:-how-to-use-bit-manipulation-to-solve-problems-easily-and-efficiently/)
- [Start Bit Manipulation Here: Good Problems](https://leetcode.com/discuss/study-guide/1150415/start-bit-manipulation-here)

  
