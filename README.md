# Unexpected Behavior of Haskell's `sort` Function

This repository demonstrates an issue encountered while using Haskell's built-in `sort` function from the `Data.List` module.  The function consistently sorts lists correctly even when the input is not in ascending order, which is not necessarily a bug but might be unexpected behavior for those unfamiliar with the implementation details. The example shows how `sort` works correctly with different input orders. 

## How to Reproduce

1.  Save the provided code as `bug.hs`.
2.  Compile and run the code using a Haskell compiler (like GHC): `ghc bug.hs && ./bug`

## Solution

The solution file `bugSolution.hs` contains the original code; it demonstrates that the behavior is expected and the `sort` function works as documented.  There is no bug to fix; the observed behavior is the intended behavior of the function.