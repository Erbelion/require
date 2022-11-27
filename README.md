# require

using require instead of import in ES6 modules
```
import { createRequire } from 'module'
const require = createRequire(import.meta.url)

const isEven = require('is-even')

console.log(isEven(2000)) // true
```
