### bitcore-message
---
https://github.com/bitpay/bitcore-message

```js
var bitcore = require('bitcore-lib');
var Message = require('bitcore-message');

var privateKey = bitcore.PrivateKey.formWIF('xxx');
var signature = Message('hello, world').sign(privateKey);

var address = 'xxx';
var signature = 'H/Dxxx';
var verified = Message('hello, world').verify(address, signature);
```

```sh
npm install bitcore-message
bower install bitcore-message
```

```
```


