# Off-by-One Error and ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: an off-by-one error leading to an `ArrayIndexOutOfBoundsException`.  The code attempts to access an array element beyond its defined size.  The solution illustrates how to correct the loop condition to prevent this error.

## Bug

The `bug.java` file contains the erroneous code. The `for` loop's condition `i <= arr.length` causes the loop to iterate one time more than it should, resulting in an attempt to access `arr[5]` which is outside the array bounds (0-4). 

## Solution

The `bugSolution.java` file provides the corrected code. The loop condition is changed to `i < arr.length` to correctly iterate through the array's valid indices. 