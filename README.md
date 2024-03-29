# AlbionKillBot
A Bot that posts kills and battles to Discord

![](https://cloud.lervo.de/index.php/apps/files_sharing/publicpreview/XHp9nBMoXzj4jPP?x=2880&y=856&a=true&file=Github_03.png)

![](https://cloud.lervo.de/index.php/apps/files_sharing/publicpreview/si36etabBERBPxQ?x=2880&y=856&a=true&file=Github_01.png)

![](https://cloud.lervo.de/index.php/apps/files_sharing/publicpreview/S6ZwxatMn8LM9T2?x=2880&y=856&a=true&file=Github_05.png)

## Simplified Instructions

 - You will need git and node.js
 - Create a bot from discord dev panel and add bot to your discord with permissions to post/read/embed in the channel you want
 - `git clone` this repository
 - `npm install` to install node dependencies

- The folder should look like this
![N|Solid](https://cloud.lervo.de/index.php/apps/files_sharing/publicpreview/SQjTJ6adcXbR5Eb?x=2880&y=856&a=true&file=Github_02.png)

 - Add bot secret token to the auth.json
 - Open auth.json and add your bot token
 - Open config.json and add your alliancetag, and channelID, alliancekey
 - `npm start`

## Detailed Instructions

- Install [Node.js](https://nodejs.org/dist/v6.11.3/node-v6.11.3-x64.msi)
- Download AlbionKillBot from the github releases and extract the .zip
- Go to [DiscordAPI](https://discordapp.com/developers/applications/me)
- Create New App
- Name it, add image(Optional) Click Create App
- Create a bot user
- Click `Show Token` Copy the Token to a text file.
- Copy `Client Secret` to a text file.
- Add `ClientID` to this link, and visit it. https://discordapp.com/oauth2/authorize?client_id=ClientID&scope=bot&permissions=84992 -Ex. https://discordapp.com/oauth2/authorize?client_id=9876543210&scope=bot&permissions=84992
- Open auth.json and add your Token. Ex. "token": "MzUxNzgeedaMzQ0.KGbeA.mIrFhCUHgwaXLU__lxc"
- In discord, enable developer mode. In discord settings, under Appearance/Advanced
- Rightclick on the channel you want the bot to post too. Then click `Copy Id`.
- Open config.json and paste `Channel ID` into channel. Ex. "Channel": "0987654321"
- Add `Alliance ID` to the config.json Ex. "AllianceTAG": "COPS"
- Go to the Albion Killboard and search for your guild. Copy the numbers at th end of the url.
- Go to https://gameinfo.albiononline.com/api/gameinfo/guilds/<!GuildID>     Replace <!GuildID> with what you copied in previous step.
- Copy the numbers after "AllianceId": and paste them into the `AllianceKey` field in config.json
- Open command window inside folder with AKBot.js

#### Type the following commands
- npm install albion-api
- npm install request
- npm install discord.io
- npm install winston

**To Run type:** node AKBot.js

*Optional to make things auto run and autorestart*
#### Type the following commands
- npm install pm2@latest -g
- npm install pm2-windows-startup -g
- pm2-startup install
- pm2 start AKBot.js
- pm2 save


## Things that WILL be added
- Commands to change setting within discord (Ex. Set alliance Tag)
- Commands for maintinance
- A way to set permissions for who can use commands
- Commands to show player/guild stats

## Using
- Discord.io
- [psykzz Albion-API](http://psykzz.com/albion-api/)

## [Discord](https://discord.gg/qcPfs6E)
- Install help, requests, ext.
