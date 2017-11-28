
`rpep-msgpack`
=====

This is a [msgpack](https://msgpack.org/index.html) serialization for [rpep.js](https://github.com/Tixit/rpep.js). RPEP is a simple, light-weight protocol for request-response and stream-event style communication between peers.

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
require.config({paths: {rpepMsgpack: '../dist/rpep-msgpack.umd.js'}})
require(['rpepMsgpack'], function(rpepMsgpack) { /* your code */ })

// global variable
<script src="rpep-msgpack.umd.js"></script>
rpepMsgpack; // rpep-msgpack.umd.js can define rpep-msgpack globally if you really
             //   want to shun module-based design
```

License
=======
Released under the MIT license: http://opensource.org/licenses/MIT