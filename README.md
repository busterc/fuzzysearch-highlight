# fuzzysearch-highlight
[![Build Status](https://travis-ci.org/uiureo/fuzzysearch-highlight.svg?branch=master)](https://travis-ci.org/uiureo/fuzzysearch-highlight)

```js
var highlight = require('fuzzysearch-highlight')

highlight('tqb', 'The quick brown fox')
//=> '<strong>T</strong>he <strong>q</strong>uick <strong>b</strong>rown fox'

highlight('quick', 'The quick brown fox', { tag: 'em' }),
//=> 'The <em>quick</em> brown fox'
```

## License
ISC
