UW Madison CS300 REVIEW

FORUMULA

midpoint=i+(k−i)/2

Sorting Algorithms

| Algorithm          | Average-Case Time    | Notes                                                                                |
| ------------------ | -------------------- | ------------------------------------------------------------------------------------ |
| **Insertion Sort** | O(n²)                | Fast only when nearly sorted                                                         |
| **Selection Sort** | O(n²)                | Always makes the same number of comparisons                                          |
| **Bubble Sort**    | O(n²)                | Even worse because of many swaps                                                     |
| **Merge Sort**     | O(n log n)           | Divides and merges efficiently                                                       |
| **Quick Sort**     | O(n log n)           | Fastest in practice; bad O(n²) worst-case if pivot chosen poorly                     |
| **Heap Sort**      | O(n log n)           | Uses a binary heap; good worst-case but slower constants than quicksort              |
| **Counting Sort**  | O(n + k)             | Non-comparison sort; only works with integers in a fixed range                       |
| **Radix Sort**     | O(nk)                | Sorts digits/characters; good for fixed-length numbers or str    ings                    |
| **Bucket Sort**    | O(n + k)             | Distributes elements into buckets; efficient for uniform data                        |
| **Shell Sort**     | O(n^(3/2)) (approx.) | Generalized insertion sort using gaps; faster than simple O(n²) sorts                |
| **Tim Sort**       | O(n log n)           | Hybrid of merge + insertion (used in Java’s `Arrays.sort()` and Python’s `sorted()`) |


🔹 Adaptive Sorting Algorithms:

Insertion Sort → Very adaptive; nearly sorted = very fast (O(n))

Bubble Sort → Adaptive if you add an early-exit flag

Merge Sort → Can be adaptive if implemented with “natural runs”

Tim Sort (used in Python and Java) → Highly adaptive, combines Merge + Insertion Sort logic

🔸 Non-Adaptive Sorting Algorithms:

Selection Sort

Heap Sort

Quick Sort (standard implementations don’t adapt)


🔹 Stable Sorting Algorithms:

Insertion Sort

Merge Sort

Bubble Sort

Counting Sort

Radix Sort

🔸 Unstable Sorting Algorithms:

Selection Sort

Heap Sort

Quick Sort (usually — unless specially modified)
