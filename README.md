# Uninitialized Property Access in C#

This repository demonstrates a common error in C#: accessing a property before it has been initialized.  Uninitialized properties will have their default values (0 for integers, null for reference types, etc.), which may not be the intended behavior.

The `bug.cs` file shows the problematic code. The `bugSolution.cs` file provides a corrected version.

## How to Reproduce

1. Clone this repository.
2. Compile and run `bug.cs`. Observe the output.
3. Compile and run `bugSolution.cs`. Observe the corrected output.