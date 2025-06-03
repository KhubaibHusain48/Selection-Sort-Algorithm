

---

# Selection Sort Algorithm in Java

## Description

This Java program implements the **Selection Sort** algorithm to sort an integer array in ascending order. Selection Sort works by repeatedly finding the minimum element from the unsorted part of the array and swapping it with the first unsorted element.

## Features

* Sorts an array of integers in ascending order.
* Prints the sorted array.
* Includes a helper method to print the array.

## Code Structure

* `SelectionSort` class with:

  * `main` method: Performs the sorting.
  * `print` method: Prints the contents of the array.

## How to Run

1. Compile the program:

   ```bash
   javac SelectionSort.java
   ```

2. Run the program:

   ```bash
   java SelectionSort
   ```

## Sample Output

```
21 23 34 45 56 98 
```

## Explanation

* The outer loop iterates through each element.
* The inner loop finds the smallest element in the unsorted portion.
* The smallest element is swapped with the element at the current position.
* After all passes, the array is sorted in ascending order.
* The `print` method displays the sorted array.

## Requirements

* Java JDK 8 or above
* Basic understanding of arrays and sorting algorithms

## License

Open source for educational and learning purposes.
