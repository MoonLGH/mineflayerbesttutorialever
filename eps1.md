1. installing things

Do
1. npm init 
2. npm install mineflayer

2.typing things

var mineflayer = require('mineflayer')

var bot = mineflayer.createBot({
  host: "server ip",   
  username: "username",
  version: "server version"
})

3. adding bot.once

bot.on('login', async () => {
    console.log(' bot is on ')
})

4. make it cool

```
var mineflayer = require('mineflayer')
 
let ip = "botattacker.aternos.me";
let username = "bot1";
let ver = "1.8.9";
var bot = mineflayer.createBot({
  host: ip,   
  username: username,
  version: ver
})

bot.on('login', async () => {
    console.log(`bot is on At ${ip}`)
})

```
