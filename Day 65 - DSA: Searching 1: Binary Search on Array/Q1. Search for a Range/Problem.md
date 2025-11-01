Problem Name: Q1. Search for a Range

## Problem Description

Given a sorted array of integers A (0-indexed) of size N, find the left most and the right most index of a given integer B in the array A.

## Problem Constraints

1 <= N <= 106
1 <= A[i], B <= 109

## Input Format

The first argument given is the integer array A.
The second argument given is the integer B.

## Output Format

## Example Input

Input 1:
A = [5, 7, 7, 8, 8, 10]
B = 8
Input 2:
A = [5, 17, 100, 111]
B = 3

## Example Output

Output 1:
[3, 4]
Output 2:
[-1, -1]

Example Explanation

## Example Explanation

Explanation 1:

The first occurrence of 8 in A is at index 3.
The last occurrence of 8 in A is at index 4.
ans = [3, 4]

Explanation 2:

There is no occurrence of 3 in the array.

## Solution

See `Solution.java` for the implementation.