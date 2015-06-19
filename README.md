# nodash

Write JavaScript code without lodash/underscore


## What's wrong with lodash/underscore ?

TODO

## New bind operator proposal to rescue !

TODO

## How-to

```js
import {assign} from 'nodash.js/object'

let obj = {a: 1}
obj::assign({b: 2}, {c: 3}) // → { 'a': 1, 'b': 2, 'c': 3 }


import {map} from 'nodash.js/collection'

let a = [1, 2, 3]
a::map(x => x * 3) // → [3, 6, 9]
```
