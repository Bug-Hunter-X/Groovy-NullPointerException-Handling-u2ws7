# Groovy NullPointerException Handling

This repository demonstrates a common issue in Groovy related to null pointer exceptions.  Groovy's dynamic typing allows for null values to be passed to methods without explicit type checking. This can lead to unexpected behavior and runtime errors if not handled properly.

The `bug.groovy` file contains a simple method that doesn't explicitly handle null arguments.  The `bugSolution.groovy` file provides a corrected version with robust null checks.

**How to reproduce:**
1. Clone this repository.
2. Run `bug.groovy` using Groovy.
3. Observe the output, demonstrating the silent failure with null arguments.
4. Run `bugSolution.groovy`, demonstrating the improved null handling.