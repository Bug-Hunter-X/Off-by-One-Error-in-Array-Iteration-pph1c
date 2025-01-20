# Off-by-One Error in Java
This repository demonstrates a common off-by-one error in Java when iterating over arrays.

The `Bug.java` file contains code with the error. The `BugSolution.java` file shows how to fix the error.

## Bug Description
The bug lies in the for loop that iterates through the array. The condition `i <= arr.length` causes the loop to iterate one time too many, resulting in an `ArrayIndexOutOfBoundsException`.