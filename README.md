# Off-by-One Error in Java
This repository demonstrates a common off-by-one error in Java array iteration and its solution.
The `bug.java` file contains code with the error, resulting in an `ArrayIndexOutOfBoundsException`. The `bugSolution.java` file provides the corrected code.
## Bug Description
The original code attempts to iterate through an array using a for loop with the condition `i <= arr.length`.  This causes an error because array indices start at 0 and end at `arr.length - 1`.
## Solution
The solution corrects the for loop condition to `i < arr.length`, ensuring that the loop does not attempt to access an index outside the array bounds.