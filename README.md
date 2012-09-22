#jq-tiles

Split images in tiles with css3 transitions.

**Demo:** http://elclanrs.github.com/jq-tiles/
**Support:** Webkit, Firefox, Opera, IE10, IE9-8*
\*_For browsers that doesn't support css3 transitions the class obvisouly won't be animated but it'll still work, just a bit choppier._
\*\*_IE8 requires polyfills for `Array.prototype.map` and `Array.prototype.forEach`. You may use [ES5 Shim](https://github.com/kriskowal/es5-shim/)._

### Options:
* **x**: number of tiles in X axis.
* **y**: number of tiles in Y axis.
* **rand**: animate effect in random order.
* **speed**: speed of effect in ms.
* **effect**: `default`, `simple`.

### Example:
```javascript
$('img').tiles({ rand: true }).trigger('toggleTiles');
```


