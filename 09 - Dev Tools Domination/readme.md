### Learnings

- Developer tool and Console rule that are super useful

- Developer tool, right click an element --> `Break on...`
  - `Subtree modification`
    - Break point when text or attribute of a child is changed
  - `Attribute modification`
    - Break point when some attribute is changed on current element
  - `node removal`
    - Break point when a child is removed

* `console.warn` adds a yellow ⚠️
* `console.error` adds a red ❌
* `console.info` adds a infomative blue ℹ️
* `console.assert` is kinda like a `if() {}`
  - If whatever is asserted is true, nothing is logged
  - If whatever is asserted is false, then log the second param
* `console.dir` displays all the attributes, properties, info for a particular element

- `console.group` is pretty dope
  - `console.groupCollapsed` logs a collapsed log
  - ```
    dogs.forEach(dog => {
      console.groupCollapsed(`${dog.name}`);
      console.log(`This is ${dog.name}`);
      console.log(`${dog.name} is ${dog.age} years old`);
      console.log(`${dog.name} is ${dog.age * 7} dog years old`);
      console.groupEnd(`${dog.name}`);
    });
    ```
    - note: `console.groupCollapsed(${dog.name});` has to have the same string as`console.groupEnd(${dog.name}`.
