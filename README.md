# nodash

Write JavaScript code without lodash/underscore


## What's wrong with lodash/underscore ?

TODO

See also: https://github.com/reindexio/youmightnotneedunderscore

## New bind operator proposal to rescue !

TODO

## How-to

```js
import {map} from 'nodash-collection'

let a = [1, 2, 3]
a::map(x => x * 3) // → [3, 6, 9]


import {partialRight} from 'nodash-function'

const mapTriple = map::partialRight(x => x * 3)
a::mapTriple() // → [3, 6, 9]
```
