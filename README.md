# PHP Ternary Operator String Interpolation Bug

This repository demonstrates a subtle bug in PHP involving the use of the ternary operator within an `echo` statement for string interpolation.  The bug arises from incorrectly handling variable interpolation within the ternary conditional expression, leading to unexpected output or parse errors. 

The `bug.php` file contains the buggy code.  The corrected version is in `bugSolution.php`.  This demonstrates the proper way to use string interpolation with the ternary operator to avoid the error.

This example highlights the importance of careful string manipulation and variable interpolation in PHP, particularly when using concise conditional logic like the ternary operator.