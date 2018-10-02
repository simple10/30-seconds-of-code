### Object from key-value pairs

Use `Array.reduce()` to create and combine key-value pairs.

```js
const objectFromPairs = arr => arr => arr.reduce((a,b) => (a[b[0]] = b[1], a), {});
```
