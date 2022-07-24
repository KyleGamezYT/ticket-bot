# 👋| Welcome to ticket-bot!
Welcome to this repository! Please dont make your own repository of this. Please keep it chill. as I dont want to file any Claims.
# 🛠|Installation
```sh
yarn install / npm install
```
Install all needed dependencies in order to work.

## Setup


❗ **permissions**

The best option is go give the bot `Administrator` permissions, but you can do it the hard way and only give the permissions it needs. Required permissions:

- Read & Send Messages ~ (obivously) If the bot isn't able to read messages or send messages, it doesn't respond to your requests.
- Manage Channels ~ (required) This is needed so the bot is able to create / edit / delete channels.
- Embed Links & Message Attachments ~ (required) Without the bot isn't able to send 9/10 messages.
- Add Reactions ~ (required) This is needed to show that the ticket owner has received the reply and to be able to setup the ticket claim system.

**Starting the bot**

It's a really simple process, first you need to rename the `.env.example` to `.env`. After that fill in the token!

## ReplIt ENV

For repl, you will have to go to the 🔒and then type in `token` in the env. Then, in the value, you type in your token. 

Do the same for the `config.json.example` file, rename it to `config.json`. Once you done that you can edit the bot's status, activity etc!

This is what it should look like:

**DISCLAIMER** The config.json is down below and it will have a few errors due to github. Please read through.

```
token:"Token here
  "prefix": "Prefix here
  "activity": "Status here
  "type": "type of status here
  "status": "dnd, online, idle or invisible goes here.
  
  "COMMENT": "Only enable hostingweb if you are using replit!",
  "hostingweb": if ur hosting on replit, use true or false
  
  "developers": ["ur id goes here"],



  "color": {
    "main"   : "#3903ff",
    "error"  : "#ff5f8e",
    "success": "#99ff9c",

    "red"   : "#ff5a48",
    "orange": "#ffca4d",
    "yellow": "#ffcc5c",
    "green" : "#74ff89",
    "purple": "#7d5eff",
    "pink"  : "#ff88d2",
    "grey"  : "#4b4b4b",
    "white" : "#ffffff"
  }
} 
```

If you remove one of the items / give them the wrong value, the bot might crash.

In order to run the bot you need to have [NodeJS](https://nodejs.org/en/), I recommend using the 16x version. To run the bot open your terminal, go to the correct directory and type `yarn run start / npm run start`, this will make a build and start the bot. After that, your done! Bot should be running without problems, yay 🎉.


## Commands And Features
You can see the commands by using slash commands. For the slash commands, the scopes need to be bot and application.commands
 
 
 ## Made with Faith, and intellegince.
