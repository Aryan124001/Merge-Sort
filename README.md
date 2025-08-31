# Merge Sort Visualization in C++

This project provides a **C++ implementation of the Merge Sort algorithm** with a step-by-step visualization of the **dividing** and **merging** phases. It helps learners understand how Merge Sort works internally.

## Features

* **Step-by-step Visualization:** Displays each dividing and merging step in real time.
* **Dynamic Input:** User can input any number of elements at runtime.
* **Efficient Sorting:** Implements the classic **divide-and-conquer** strategy.
* **Simple CLI Interface:** Easy to compile and run.

## How Merge Sort Works

1. **Divide:** Recursively split the array into two halves until single elements remain.
2. **Conquer:** Merge the halves while sorting them in ascending order.
3. **Combine:** Continue merging until the entire array is sorted.

---

## Example Output

```plaintext
Enter the number of elements: 5
Enter the elements: 8 3 7 4 2

Initial array: [8, 3, 7, 4, 2]
Dividing: [8, 3]
Dividing: [7, 4, 2]
Merging: [3, 8]
Merging: [4, 7]
Merging: [2, 4, 7]
Merging: [2, 3, 4, 7, 8]

Sorted array: [2, 3, 4, 7, 8]
```

---

## Prerequisites

* **C++ Compiler** (e.g., `g++`) with C++11 or later support.

---

## How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Aryan124001/Merge-Sort.git
   cd Merge-Sort
   ```

2. **Compile the Program**

   ```bash
   g++ -o merge_sort main.cpp
   ```

3. **Run the Executable**

   ```bash
   ./merge_sort
   ```

---

## Algorithm Complexity

* **Time Complexity:** O(n log n)
* **Space Complexity:** O(n)
