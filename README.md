### Code Refactoring Challenge

**Initial Code:**
```javascript
let globalVar = 10;

function addValue(x) {
  return x + globalVar;
}

function multiplyByGlobal(y) {
  return y * globalVar;
}

function updateGlobal(newValue) {
  globalVar = newValue;
}

// Example usage
console.log(addValue(5)); // Output: 15
console.log(multiplyByGlobal(2)); // Output: 20
updateGlobal(5);
console.log(addValue(5)); // Output: 10
```

**Challenge:**
Refactor the given code to use lexical scoping instead of relying on global variables. Ensure that the functions are self-contained and do not depend on variables outside of their lexical scope. The goal is to encapsulate variables within the appropriate scope and reduce reliance on global state.
