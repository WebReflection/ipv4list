# ipv4list
log or returns a list of all available ipv4 addresses 

```bash
# suggested as global
sudo npm install -g ipv4list

# output
ipv4list
```

It is possible to have an object instead of a formatted JSON output
using `ipv4list` as module instead of global executable.

```js
# npm install ipv4list

var ipv4list = require('ipv4list');

console.log(ipv4list);
```