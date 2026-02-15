# Modified Whatsapp-API
<p align='center'>
  <img src="https://l.top4top.io/p_3658lopcf1.jpg" width="500">
</p>

--- 

## Usage
```json
"depencies": {
  "xatabail": "github:Bealllevey62/xatabail"
}
```
## Import
```javascript
const {
  default:makeWASocket,
  // Other Options 
} = require('xatabail');
```

---
# How To Connect To Whatsapp
## With QR Code
```javascript
const {
  default: makeWASocket
} = require('xatabail');

const client = makeWASocket({
  browser: ['Ubuntu', 'Chrome', '20.00.1'],
  printQRInTerminal: true
})
```
