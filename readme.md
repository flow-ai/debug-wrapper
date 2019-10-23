# debug-wrapper

 debug-wrapper goal is to avoid logging to stderr by default. 
 Usage you can use it
 ```js
const {debug, error} = require('debug-wrapper').all('namespace:subnamespace');

debug('debug'); //goes to stdout
error('error'); //goes to stderr
```