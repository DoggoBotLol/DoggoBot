# Doggo

A cool multi purpose discord bot with commands for Fun, Moderation, Utility, Image and Animals also with owner only commands !!

[Add It](https://discord.com/api/oauth2/authorize?client_id=818092139496996864&permissions=8&scope=bot) | [Join Our Discord](https://discord.gg/RWSEj6JrjJ)

[![DiscordBanner](https://invidget.switchblade.xyz/RWSEj6JrjJ)](https://discord.gg/RWSEj6JrjJ)

![LOC](https://tokei.rs/b1/github/Dinav69/DoggoBot?category=code)

## How to setup 

### Creating a Bot and adding to your server

◙ Go to `Discord Developer Portal` by [clicking here](https://discord.com/developers/applications)

◙ Click on to `New Application` and then name your application

◙ Selct the application you will see bot just under `OAuth2` select that

◙ Press `Add Bot`

◙  Then go to `OAuth2` to get the bot's invite link

◙ Under scopes you'll see bot click that and under you see `Bot Permissions` select the permissions

◙ Copy the invite link which is generated on the `Scopes`

◙ Go to bot tab then you'll see `TOKEN` click copy 

◙ Make sure you turn on both the intends in your you'll find that in that bot category !!

And now you got the token !!!

## Configuring

Make a `.env` file and then:
```
TOKEN=Replace with your bot's token that I just explained how to obtain
YT_KEY=YouTube API Key for Youtube Command
IMBD_KEY=IMBD api key for the Movie Command
GOOGLE_KEY=The Goole api search engine key for Google Command
ENGINE_ID=The search engine ID for Google Command
```
Search `GOOGLE_KEY` & `ENGINE_ID` can be obtained from [here](https://cse.google.com/cse/), `YT_KEY` from [here](https://console.cloud.google.com/apis/library/youtube.googleapis.com?q=you&id=125bab65-cfb6-4f25-9826-4dcc309bc508&project=ninth-psyche-296311) and `IMDB_KEY` from [here](https://developer.imdb.com/)

**Do not put any commas or anything on `.env` file's value !!**

Go to `config.json` and then:
```js
{
    "Prefix": "The prefix that you need for your bot",
    "Owner": "You ID",
    "Invite": "You bot's invite link that we just explained how to obtain",
    "Server": "Your bot's support server"
}
```

**Channel Setup**

go to `channels.json`

```js
{
    "ServerLogs": "ID of channel that you wann receive the bot's server logs",
    "Feeback": "ID of the channel that you wanna get the feedback of the bot",
    "Report": "Id of the channel that you wanna get the reports of the bot",
    "Suggestion": "ID of the channel that you wanna get the suggestions of the bot"
}
```

If you need to change the emojis go to `emoji.json` and change it I recommend the value to be same as it is

## Starting the Bot

**Things that are required**

[Node.js](https://nodejs.org/en/)

[Git](https://git-scm.com/)

[Discord](https://discord.com/)

[Visual Studio Code](https://code.visualstudio.com/download)

◙ Then first to install the packages open a terminal in visual studio code type `npm install`

![terminal](https://user-images.githubusercontent.com/45940386/111021871-b22ee080-83e8-11eb-92cb-c2ff2ccc7b3f.png)

◙ Then after the packages and intalled and things are been configured in the `config.json`

◙ Go to the terminal type `node index.js`

![terminal2](https://user-images.githubusercontent.com/45940386/111021908-e1dde880-83e8-11eb-8799-5a1b95b9998a.png)

◙ After a few seconds (well maybe more all according to you network) you'll see `<your bot's user> is now connected to Discord`

![terminal3](https://user-images.githubusercontent.com/45940386/111021941-236e9380-83e9-11eb-9a5c-b66e96f16ade.png)

**And that's for the self hosting**
