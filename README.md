```js
Object.prototype.tap = function(f) { f(this); return this; };
```
<!-- Object.defineProperty(Object.prototype, "tap", {value: function(f) { f(this); return this; }}); -->
