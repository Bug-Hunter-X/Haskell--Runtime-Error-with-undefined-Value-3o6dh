# Haskell Undefined Value Bug

This repository demonstrates a common runtime error in Haskell caused by the use of the `undefined` value. The `undefined` value represents a computation that has no defined result. Attempting to use it in an expression will lead to a runtime exception.

The `bug.hs` file contains the erroneous code. The `bugSolution.hs` file provides a corrected version.

**Error:** The program crashes with a runtime error because it tries to perform arithmetic on an undefined value.

**Solution:** The solution involves replacing `undefined` with a suitable default value or handling the possibility of an undefined value more gracefully (e.g., using pattern matching or the Maybe monad).