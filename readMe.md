# Longest Increasing Subsequence

This Python code provides three different algorithms to find the length of the longest increasing subsequence in an unsorted array of integers.

## Problem Description

Given an unsorted array of integers, the task is to find the length of the longest increasing subsequence. An increasing subsequence is a sequence of numbers in which each element is larger than the previous one.

### Example

**Input:**
```
[10, 9, 2, 5, 3, 7, 101, 18]
```

**Output:**
```
4
```

**Explanation:**
The longest increasing subsequence is `[2, 3, 7, 101]`, and its length is 4.

## Algorithms

1. **Dynamic Programming Algorithm**
   - Time Complexity: O(n^2)
   - Space Complexity: O(n)

2. **Optimized Dynamic Programming Algorithm with Segment Tree**
   - Time Complexity: O(nlogx), where x is the max element in the list
   - Space Complexity: O(x), where x is the max element in the list
   - Note: If the max element is larger than 10^5, it is recommended to use `longest_increasing_subsequence_optimized2()`.

3. **Optimized Dynamic Programming Algorithm with Segment Tree (Alternative)**
   - Time Complexity: O(nlogn)
   - Space Complexity: O(n)

## Usage

The code includes a simple command-line interface to demonstrate how to use these algorithms. Ensure that you provide the source file and destination file as command-line arguments when running the script.

```bash
python script.py source_file.txt compressed_file.bin
```

Replace `script.py`, `source_file.txt`, and `compressed_file.bin` with your actual script name, source file, and destination file.

Feel free to explore and compare the different algorithms based on their time and space complexities for your specific use case.