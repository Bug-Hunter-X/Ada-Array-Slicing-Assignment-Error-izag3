# Ada Array Slicing Assignment Bug

This repository demonstrates a common error in Ada programming related to array slicing.  Ada does not support direct slicing assignment like some other languages (e.g., Python). This example shows the incorrect and correct ways to handle array slices.

## Bug Description

The bug arises from attempting to assign a slice of one array to another array variable without iterating through the slice elements.  The compiler will detect this as an error.

## Solution

The correct way is to assign the slice element by element.