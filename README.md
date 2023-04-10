# Gamecord
A Code that allows you to get the "Playing" Discord Status without playing any games!

----

The [index.js](https://github.com/SealedSaucer/Gamecord/blob/main/index.js) is the main file. [server.js](https://github.com/SealedSaucer/Gamecord/blob/main/server.js) prevents your repl from going to sleep. (If you have a replit hacker plan, then you can delete [this file](https://github.com/SealedSaucer/Gamecord/blob/main/server.js) and paste this code inside the [index.js](https://github.com/SealedSaucer/Gamecord/blob/main/index.js) file : 

</br>

```js
const dotenv = require('dotenv');
const TOKEN = (process.env.TOKEN);
const { Client } = require('discord.js-selfbot-v11')
const client = new Client();

client.on('ready', () => { 
  client.user.setActivity("Cyberpunk 2077", { type: "PLAYING"})
   console.log(`${client.user.username} Successfully Logged in!`)
})

client.login(TOKEN);
```



**DO NOT GIVE YOUR TOKEN TO OTHERS!**

Use [uptimerobot.com](https://uptimerobot.com) to make your repl online 24/7.

</br>

> ⭐ Feel free to Star the Repository if this helped you! ;)

----

> Gamecord 
