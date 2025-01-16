# Unexpected Behavior with Mutable Variables in F#

This example demonstrates a common pitfall when working with mutable variables in F#.  The `swap` function intends to swap the values of `x` and `y`, but due to how mutable variables are handled, it doesn't produce the expected output.

The `bug.fs` file contains the code exhibiting the unexpected behavior. The `bugSolution.fs` file provides a corrected version using techniques to avoid this issue. 