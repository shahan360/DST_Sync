Problem Name: Q1. Insert that

## Problem Description

Write a program to input N numbers array, a number X and a number Y from user and insert an element Y in it at specified position X. X is based on 1-based indexing

Note: When an element is inserted at position X, all elements that were already present at position >= X, gets shifted to one position right, not replaced.

## Problem Constraints

1 <= N <= 100

1 <= A[i] <= 1000

1 <= X <= N

1 <= Y <= 1000

## Input Format

N numbers array, a number X and a number Y from user and insert an element Y in it at specified position X. X is based on 1-based indexing

Note: When an element is inserted at position X, all elements that were already present at position >= X, gets shifted to one position right, not replaced.

Problem Constraints

1 <= N <= 100

1 <= A[i] <= 1000

1 <= X <= N

1 <= Y <= 1000

Input Format

First line is N which represents number of elements.

Second line contains N space separated integers.

Third line is X position where Y has to be inserted.

Fourth line is Y which is the value to be inserted.

## Output Format

N+1 space separated integers of the input array after inserting the element at required position.

## Example Input

Input 1:
5

2 3 1 4 2

3

5

## Example Output

Output 1:
Example Explanation

## Example Explanation

Explanation 1:

Clearly after inserting 5 at 3rd position, new array is 2 3 5 1 4 2.

Note:

This question requires you to read a list of integers from input using the map() function.
Since this concept will be covered later in the module, we encourage you to do some independent research and write your code accordingly.
You may also refer to the following article for further guidance: link
1
2
3
4
5
6
7
8
9
10
11

## Solution

See `Solution.py` for the implementation.