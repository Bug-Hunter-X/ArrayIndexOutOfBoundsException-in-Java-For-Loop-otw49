# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that causes this exception. The `bugSolution.java` file provides the corrected code.

## Description
The error occurs when the program tries to access an array element using an index that is outside the valid range of indices for that array.  In Java, arrays are zero-indexed, so a valid index for an array of size n is 0 to n-1.

## How to reproduce
1. Compile `bug.java`.
2. Run the compiled code.  Observe the `ArrayIndexOutOfBoundsException`. 

## Solution
The corrected code in `bugSolution.java` shows how to prevent this error by ensuring the loop iterates within the valid index range of the array.