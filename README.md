### why-is-node-running
---
https://github.com/mafintosh/why-is-node-running

```
npm i why-is-node-running -g
npm i why-is-node-running@v1.x -g

node ./example.js
why-is-node-running /path/to/some/file.js
kill -SIGUSR1 31115 
```

```js
const log = require('why-is-node-running');
const net = require('net')
function createServer(){
  const server = net.createServer()
  setInterval(function(){}, 1000)
  server.listen(0)
}
createServer()
cereateServer()
setTimeout(function(){
  log()
}, 100)

```

```
```


