# Data-Engineering-Algorithms

Graduate coursework repository implementing core algorithms for data processing, complexity analysis, and scalability reasoning in data engineering contexts.

---

## 1. Title and Summary

**Data Engineering Algorithms**  
Northwestern University M.S. in Data Science (Data Engineering specialization): Jupyter-based implementations and empirical benchmarks of sorting, search, graph, dynamic programming, and greedy algorithms, with Big O analysis tied to data-intensive processing design.

---

## 2. Concepts and Methods

- **Comparison sorting:** selection sort, bubble sort, insertion sort, and quicksort (divide-and-conquer with pivot partitioning); empirical timing across increasing input sizes
- **Search algorithms:** linear search, binary search on sorted collections, and average-case lookup via Python `set` membership (hash-based O(1) retrieval)
- **Recursion vs. iteration:** factorial computed recursively and with a `for` loop; stack-depth and execution-time comparison
- **Graph traversal:** breadth-first search (BFS) over a multi-level adjacency-list graph using `collections.deque`; shortest-path routing with **Dijkstra's algorithm** on a weighted `networkx` graph (NYC to LA route scenario)
- **Dynamic programming:** bottom-up solution to the **Boolean Parenthesization Problem** (`T`/`F` symbols with `&`, `|`, `^` operators); 2D tables `T[i][j]` and `F[i][j]` for subexpression counts
- **Greedy scheduling:** cost-minimizing security-guard shift assignment under hourly and overtime wage rules
- **Complexity analysis:** Big O notation for each algorithm (e.g., O(n²), O(n log n), O(log n), O(n+e), O(n³)); discussion of scalability implications for data-intensive systems
- **Empirical benchmarking:** controlled random seeds, `time` / `datetime` timing, `pandas` summary tables, and `matplotlib` plots of input size vs. execution time

---

## 3. Stack

| Layer | Tools |
|-------|-------|
| Language | Python 3 |
| Environment | Jupyter Notebook |
| Numerics / tables | NumPy, pandas |
| Visualization | matplotlib |
| Graphs | NetworkX |
| Utilities | `collections.deque`, `iteration_utilities`, `time`, `random`, `string` |

---

## 4. Structure

```
Data-Engineering-Algorithms/
├── Selection Sort Algorithm.ipynb
├── Quick Sort Algorithm .ipynb
├── Binary Search Algorithm.ipynb
├── Recursive Algorithms and Iterative Algorithms .ipynb
├── Hash Functions.ipynb
├── Breadth-First Search Algorithm.ipynb
├── Dijkstra's Algorithm.ipynb
├── Dynamic Programming Algorithm .ipynb
├── Greedy Algorithm.ipynb
└── README.md
```

- **Organization:** flat layout; one notebook per algorithm assignment with embedded narrative reports (Introduction, Methodology, Analysis & Results, Big O Discussion, Conclusion)
- **Reusable modules:** none; logic lives in notebook cells rather than importable packages
- **Engineering practice:** reproducible random seeds, timed benchmarks at multiple input scales, tabular and visual comparison of algorithm variants, and written analysis connecting algorithm choice to operational scalability

---

**Course context:** Northwestern University, M.S. in Data Science, Data Engineering specialization  
**Repository:** https://github.com/EAName/Data-Engineering-Algorithms
