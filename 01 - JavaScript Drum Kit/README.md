### Learnings

- `const keys = document.querySelectorAll(".keys");` returns NodeList, so I cannot `addEventListener` directly to that.
  - I need to `forEach` or `map` for each item in the array, in order to `addEventListener`
    - i.e. `keys.forEach(item => item.addEventListener('eventToListenTo'), insertFunctionHere);`
