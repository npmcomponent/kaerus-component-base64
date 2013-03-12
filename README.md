base64
======

base64 encoder / decoder 

Usage
=====

```
> a = require('./index')
{ encode: [Function],
  decode: [Function],
  encodeURL: [Function],
  decodeURL: [Function] }

> a.encode("fool")
'Zm9vbA=='

> a.decode('Zm9vbA==')
'fool'

> a.decodeURL('aGVsbG8gd29ybGQ_')
'hello world?'
```