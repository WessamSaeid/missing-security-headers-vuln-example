# missing-security-headers-vuln-example

## there is 5 vulnerabilities

1. Missing X-Frame-Options header in `index.vuln.js` line `1`
2. Missing X-Content-Type-Options header in `index.vuln.js` line `1`
3. Missing Content-Security-Policy header in `index.vuln.js` line `1`
4. Missing X-XSS-Protection header in `index.vuln.js` line `1`
5. Missing Strict-Transport-Security header in `index.vuln.js` line `1`

```js
const express = require('express')
const helmet = require('helmet')

var bodyParser = require('body-parser')
 
var app = express()

```