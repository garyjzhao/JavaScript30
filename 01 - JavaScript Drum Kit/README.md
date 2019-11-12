### Learnings

- `const keys = document.querySelectorAll(".keys");` returns NodeList, so I cannot `addEventListener` directly to that.
  - I need to `forEach` or `map` for each item in the array before I can do something with it
    - i.e. `keys.forEach(item => item.addEventListener('eventToListenTo'), insertFunctionHere);`
