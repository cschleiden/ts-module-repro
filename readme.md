Problem: 

`types.d.ts` is not compiled to a module, yet `index.js` tries to export from it:

```js
export * from "./types";
export * from "./component";
```