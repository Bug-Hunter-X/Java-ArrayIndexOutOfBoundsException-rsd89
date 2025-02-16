# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`.  The `Bug.java` file contains the erroneous code, while `BugSolution.java` provides a corrected version.

The bug arises from attempting to access an array element using an index that is outside the valid range of indices for the array.  Java arrays are zero-indexed, so a valid index ranges from 0 to array.length - 1.

This example highlights the importance of careful array index checking to prevent runtime exceptions.