
`rpep-msgpack`
=====

This is a [msgpack](https://msgpack.org/index.html) serialization for [rpep.js](https://github.com/Tixit/rpep.js) using [kawanet/msgpack-lite](https://github.com/kawanet/msgpack-lite). RPEP is a simple, light-weight protocol for request-response and stream-event style communication between peers.

Install
=======

```
yarn install rpep-msgpack
```

Usage
=====

Accessing rpep:
```javascript
// node.js
var rpepMsgpack = require('rpep-msgpack')

// amd
require.config({paths: {rpepMsgpack: '../dist/rpepMsgpack.umd.js'}})
require(['rpepMsgpack'], function(rpepMsgpack) { /* your code */ })

// global variable
<script src="rpepMsgpack.umd.js"></script>
rpepMsgpack; // rpepMsgpack.umd.js can define rpepMsgpack globally if you really
             //   want to shun module-based design
```

License
=======
Released under the MIT license: http://opensource.org/licenses/MIT