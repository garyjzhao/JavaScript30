### Learnings

- Some and Every Check

  - Thankfully they are pretty straighforward
  - In an array,
    - `.some()` checks if there is at least one that returns true
    - `.every()` checks if all is true

- `.find()`
  - Finds literally goes and finds what we are looking for
- `.findIndex()`
  - Goes out to find the index of what we are looking for
  - returns index, i.e. `array[1]` <- that "one"

* Creating a new array to perserve the previous array using spread operator
  - `...comments.slice(0, index)`
    - spread what is from the first index up until the index across the new array
  - `...comments.slice(index + 1)`
    - spread from designated index + 1 until the end of the array
