### Learnings

- `NodeList` vs `Array`
  - `Nodelist` has fewer functions available
    - For exampple: `forEach`, no `map`
- `document.documentElement.style.setProperty`
  - `document` ==> the document
  - `documentElement` ==> the `:root`
  - `style` nuff said
  - `setProperty` ==> sets the property. Takes two arguments
- `this.dataset`
  - `this.dataset` retrieves all the data attributes on the element
- after much playing around, I cannot seem to get `handleChange()` to use arrow functions instead... :/
