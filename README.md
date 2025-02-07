# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common error in Java: the `ArrayIndexOutOfBoundsException`. The code attempts to access an array element beyond its valid index range, resulting in a runtime exception.

The `bug.java` file contains the erroneous code.  The `bugSolution.java` file provides the corrected version.

The error is a classic off-by-one error. The loop condition `i <= arr.length` should be `i < arr.length` to prevent accessing the element at index 5 (which is out of bounds for a size 5 array).