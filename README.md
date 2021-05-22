#Discord.js-Oneline
```js
const Discord = require('discord.js-oneline');

Discord.Oneline("TOKEN", "PREFIX");
```

#Command Handler
```js
module.exports.run = async function(client, message, args) {
//code
}

module.exports.help = {
name: "",
}
```


#Event Handler
```js
module.exports.run = async function(client, message, args) {
//code
}

module.exports.help = {
name: "",
once: false
}
```
