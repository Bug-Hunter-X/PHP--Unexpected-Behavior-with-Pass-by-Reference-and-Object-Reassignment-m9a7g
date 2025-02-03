# PHP Object Reference Bug

This repository demonstrates a subtle bug in PHP related to object references and pass-by-reference function parameters.  The issue arises when a new object is assigned to a pass-by-reference parameter; this breaks the reference, leaving the original object unchanged.

The `bug.php` file showcases the problematic behavior, while `bugSolution.php` illustrates how to correctly handle this scenario to avoid the unintended outcome.

The bug is thoroughly explained in the `bug.php` file's comments, along with a discussion of the root cause and the correct approach.  The solution in `bugSolution.php` provides a clear and concise alternative.