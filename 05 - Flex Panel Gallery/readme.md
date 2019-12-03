### Learnings

- `document.querySelectorAll` returns a NodeList, so we can only use `forEach`
- Event Listen for a `transitionend` to help with listening to when a transition occurs
  - To find out which property occurs, run `console.log(event.propertyName)`
