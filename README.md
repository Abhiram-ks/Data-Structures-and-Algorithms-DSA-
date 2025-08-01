# Why DSA? 

Learning DSA isn't just about algorithms, it's about developing a mindset to think critically and solve problems creatively. When I started my project, I realized how much DSA enhanced my ability to find efficient solutions. This experience showed me how important it is to know the basics to build better and more useful projects.

DSA is like the fitness test for engineers, it doesn't mean you'll be lifting heavy weights right away, but it shows you've got the potential to get stronger.
Node: Welcome to the Data Structures and Algorithms (DSA) repository written in Dart designed for developers who want to master the core fundamentals of DSA using a modern, clean, and object-oriented language.

# What is DSA?

- Data Structures: are techniques to organize and store data efficiently.  
- Algorithms: are step-by-step procedures or logic used to solve computational problems.

Together, they help build fast | efficient | scalable | optimized 


#  Time & Space Complexity Table (for DSA)

| Operation       | Array / List | Linked List | Stack | Queue | Hash Map | Set  | Binary Tree | Heap     |
| --------------- | ------------ | ----------- | ----- | ----- | -------- | ---- | ----------- | -------- |
| Access          | O(1)         | O(n)        | O(n)  | O(n)  | N/A      | N/A  | O(log n)    | O(1)     |
| Search          | O(n)         | O(n)        | O(n)  | O(n)  | O(1)     | O(1) | O(log n)    | O(n)     |
| Insertion (End) | O(1)\*       | O(1)        | O(1)  | O(1)  | O(1)     | O(1) | O(log n)    | O(log n) |
| Deletion (End)  | O(1)         | O(n)        | O(1)  | O(1)  | O(1)     | O(1) | O(log n)    | O(log n) |
| Insertion (Mid) | O(n)         | O(1)\*      | O(n)  | O(n)  | N/A      | N/A  | O(log n)    | -        |
| Deletion (Mid)  | O(n)         | O(1)\*      | O(n)  | O(n)  | N/A      | N/A  | O(log n)    | -        |

#  Common Sorting Algorithms – Time & Space Complexity

| Algorithm      | Best Time  | Average Time | Worst Time | Space    |
| -------------- | ---------- | ------------ | ---------- | -------- |
| Bubble Sort    | O(n)       | O(n²)        | O(n²)      | O(1)     |
| Selection Sort | O(n²)      | O(n²)        | O(n²)      | O(1)     |
| Insertion Sort | O(n)       | O(n²)        | O(n²)      | O(1)     |
| Merge Sort     | O(n log n) | O(n log n)   | O(n log n) | O(n)     |
| Quick Sort     | O(n log n) | O(n log n)   | O(n²)      | O(log n) |
| Heap Sort      | O(n log n) | O(n log n)   | O(n log n) | O(1)     |
| Counting Sort  | O(n + k)   | O(n + k)     | O(n + k)   | O(k)     |
| Radix Sort     | O(nk)      | O(nk)        | O(nk)      | O(n + k) |

# Searching Algorithms – Time & Space Complexity

| Algorithm        | Time Complexity       | Space              |
| ---------------- | --------------------- | ------------------ |
| Linear Search    | O(n)                  | O(1)               |
| Binary Search    | O(log n)              | O(1) or O(log n)\* |
| Hashing (Search) | O(1) avg / O(n) worst | O(n)               |

#  Recursion & Divide and Conquer
| Technique             | Time (Typical) | Space (due to recursion) |
| --------------------- | -------------- | ------------------------ |
| Factorial (Recursion) | O(n)           | O(n)                     |
| Fibonacci (naive)     | O(2ⁿ)          | O(n)                     |
| Fibonacci (DP)        | O(n)           | O(n)                     |
| Merge Sort            | O(n log n)     | O(n)                     |
| Quick Sort            | O(n log n) avg | O(log n) stack           |

# Graph Algorithms
| Algorithm       | Time Complexity  | Space |
| --------------- | ---------------- | ----- |
| DFS (Adj List)  | O(V + E)         | O(V)  |
| BFS (Adj List)  | O(V + E)         | O(V)  |
| Dijkstra (Heap) | O((V + E) log V) | O(V)  |
| Bellman-Ford    | O(VE)            | O(V)  |
| Floyd-Warshall  | O(V³)            | O(V²) |
| Kruskal’s MST   | O(E log E)       | O(V)  |
| Prim’s MST      | O(E + log V)     | O(V)  |

# Dynamic Programming – Common Examples
| Problem                     | Time        | Space     |
| --------------------------- | ----------- | --------- |
| 0/1 Knapsack (DP)           | O(nW)       | O(nW)     |
| Longest Common Subsequence  | O(n·m)      | O(n·m)    |
| Matrix Chain Multiplication | O(n³)       | O(n²)     |
| Coin Change (Min Coins)     | O(n·amount) | O(amount) |
