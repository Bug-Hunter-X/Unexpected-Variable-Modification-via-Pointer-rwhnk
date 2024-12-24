# Unexpected Variable Modification via Pointer in C

This repository demonstrates a common error in C programming involving pointer arithmetic and variable modification. The `bug.c` file contains code that unexpectedly modifies a variable through a pointer.  The `bugSolution.c` file offers a corrected version and explanation.

The error lies in a misunderstanding of how pointers work. Modifying the value pointed to by a pointer directly modifies the original variable.  This can be problematic if not carefully managed.