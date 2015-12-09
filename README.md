# DiscordJSON
Discord Javascript JSON api

### Dependecies
+ Javascript Parser: **Node.js** 
+ Javascript api: **Discord.js**

## Layout
How to setup Discord.json

### authentication
```json
"auth":{
  "username":"<enter username here>",
  "password":"<enter password here>"
}
```
### status
```json
"status":{
  "activity":"<online or away, the bots current activity status>",
  "game":"<a discord friendly game eg. fallout, half life 2, etc>"
}
```
### dependecies
**warning** do not edit this section as it is preset.
### commands
```json
"commands":{
  "<command name>":{
    "description":"<command description>",
    "action":"<command action, what does it do>"
  }
}
```
