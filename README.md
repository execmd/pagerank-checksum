pagerank-checksum
=================

Library for calculating pagerank checksum on Node.JS or plain javascript

Usage:
Node.JS
```javascript
var domain = 'http://github.com';
var pagerankCH = require('./<path to lib>/index.js');
console.log('PageRank checksum for domain %s is: %s', domain, pagerankCH(domain));
```
Result:
```
PageRank checksum for domain http://github.com/ is: 713096955383
```
