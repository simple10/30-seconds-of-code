### Count occurrences of a value in array

Use `reduce()` to increment a counter each time you encounter the specific value inside the array.

```js
const countOccurrences = (arr, value) => arr.reduce((a, v) => v===value ? a + 1 : a + 0, 0);
```
