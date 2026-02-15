# Modified Whatsapp-API
<p align='center'>
  <img src="https://l.top4top.io/p_3658lopcf1.jpg" width="500">
</p>

--- 

## Usage
```json
"depencies": {
  "azzbail": "github:AzzOffcialori/AzzMeilia"
}
```
## Import
```javascript
const {
  default:makeWASocket,
  // Other Options 
} = require('azzbail');
```

---
# How To Connect To Whatsapp
## With QR Code
```javascript
const {
  default: makeWASocket
} = require('azzbail');

const client = makeWASocket({
  browser: ['Ubuntu', 'Chrome', '20.00.1'],
  printQRInTerminal: true
})
```
