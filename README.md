UW Madison CS300 REVIEW

FORUMULA

midpoint=i+(k−i)/2

Sorting Algorithms

| **Algorithm**      | **Best-Case** | **Average-Case** | **Worst-Case** | **Stable?** | **Adaptive?** | **Space Complexity**           | **Notes**                                                                |
| ------------------ | ------------- | ---------------- | -------------- | ----------- | ------------- | ------------------------------ | ------------------------------------------------------------------------ |
| **Insertion Sort** | O(n)          | O(n²)            | O(n²)          | ✅ Yes       | ✅ Yes         | **O(1)**                       | Fast only when nearly sorted; simple and in-place.                       |
| **Selection Sort** | O(n²)         | O(n²)            | O(n²)          | ❌ No        | ❌ No          | **O(1)**                       | Always makes the same number of comparisons; not adaptive.               |
| **Bubble Sort**    | O(n)          | O(n²)            | O(n²)          | ✅ Yes       | ✅ Yes         | **O(1)**                       | Detects sorted lists early; simple but inefficient.                      |
| **Merge Sort**     | O(n log n)    | O(n log n)       | O(n log n)     | ✅ Yes       | ❌ No          | **O(n)**                       | Divides and merges efficiently; requires extra memory.                   |
| **Quick Sort**     | O(n log n)    | O(n log n)       | O(n²)          | ❌ No        | ❌ No          | **O(log n)** (recursive stack) | Fastest in practice; bad worst case if pivot chosen poorly.              |
| **Heap Sort**      | O(n log n)    | O(n log n)       | O(n log n)     | ❌ No        | ❌ No          | **O(1)**                       | Uses a binary heap; good worst case but slower constants than quicksort. |
| **Shell Sort**     | O(n log n)*   | O(n^1.5)         | O(n²)          | ❌ No        | ✅ Yes         | **O(1)**                       | Generalized insertion sort with gap sequence; adaptive to partial order. |



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
