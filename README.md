# Relative Sort

LeetCode Q # 1122.

Given two arrays arr1 and arr2, the elements of arr2 are distinct, and all elements in arr2 are also in arr1.
Sort the elements of arr1 such that the relative ordering of items in arr1 are the same as in arr2. Elements that do not appear in arr2 should be placed at the end of arr1 in ascending order.

Example 1:

>Input: arr1 = [2,3,1,3,2,4,6,7,9,2,19], arr2 = [2,1,4,3,9,6]</br>
>Output: [2,2,2,1,4,3,3,9,6,7,19]</br>

Example 2:

>Input: arr1 = [28,6,22,8,44,17], arr2 = [22,28,8,6]</br>
>Output: [22,28,8,6,17,44]

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Relative-Sort-LeetCode/assets/171427226/3da0c8e9-10aa-4f1d-9cb5-5bcd2df4284f)

  Time complexity: O(n^2).</br>Space complexity: O(1).
</div>
