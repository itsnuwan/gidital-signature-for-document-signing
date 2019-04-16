# Digital signature from javascript crypto

This repository contains code sample of nodejs crypo built in library usage for digital signature of document signing.

Read more details of javascript cypto library [here](https://nodejs.org/docs/v0.4.2/api/all.html#crypto)

## Plaform dependencies
- NodeJs >= v10.15

## Files and directories
- `./keys`  - Directory contains sample public and private key.You MUST generate your own key for real usage.Refer keys/README.md for how to generate your own keys 
- `signature.txt` - sign.js will write generated signature on this file.It will be overritten each time you run sign.js
- `sample-doc.txt` - This is a sample document to be signed.You can use any document type for this.Just change the document path of sign.js and verify.js files accordingly.
- `sign.js` - Code script to generate digital signature
- `verify.js` - Code script to verify generated gidital signature

## Usage

### Generate the signature by using keys/privateKey.pem for the document sample-doc.txt
```
node sign.js
```
### Verify the signature generated from above step(stored in signature.txt)
```
node verify.js
```

## Todos
 - Write MORE Tests
 - ES6

License
----

MIT


**Free Software, Hell Yeah!**
