# Swift Array Immutability with map()

This repository demonstrates a subtle but important aspect of Swift's array handling:  the immutability of arrays when using functional methods like `map()`. The provided code shows how `map()` creates a *new* array without modifying the original. This behavior can be unexpected for developers familiar with other languages that allow in-place modification of arrays during iteration.