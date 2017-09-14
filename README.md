# sensitive-words


# Example

```shell
$ npm install sensitive-words --save
```

```javascript
const {sensitiveWords} = require('sensitive-words')
//ES2015 Modules
import {sensitiveWords} from sensitive-words
const filtered = sensitiveWords('The new apple macbook pro is awesome', ['pro', 'new'])
console.log('filtered=>', filtered);
//The ***** apple macbook ***** is awesome
```
