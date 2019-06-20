# C3C
<img alt="vulnerabilities" src="https://img.shields.io/snyk/vulnerabilities/github/lequanglam/c3c.svg?style=flat-square"> <a href="https://discord.gg/2A4bYJu"><img alt="discord" src="https://img.shields.io/discord/591223706643070976.svg?style=flat-square"></a> <img alt="reposize" src="https://img.shields.io/github/repo-size/lequanglam/c3c.svg?style=flat-square"> <img alt="codesize" src="https://img.shields.io/github/languages/code-size/lequanglam/c3c.svg?style=flat-square">

A bot that can be customized using plugins. Currently supports Facebook Messenger (using facebook-chat-api) and Discord (using discord.js)

## Install
Install Node.JS and Git if you don't have one, then clone this repository.
Go to the directory where you store this repository, then type: 
```bash
npm install
``` 
and you are ready to go.

## Usage
```bash
node index.js
```

If this is the first time you execute this command, it'll generate `config.json` file. Close that command and then configure `config.json` file.

After that, you can run that command again and bot will go live.

## Plugins
Currently, there's only 2 plugins writen by me: 
- SimSimi (/plugins/SimSimi.z3p)

-- Main function: Allow users to chat with SimSimi.
- Economy (/plugins/Economy.z3p)

-- Main function: Create an economy.

## Localize
This bot is in early state, so only EN are supported and `language` in config has no function.

## Facebook test accounts
A Facebook test account is an account just like normal accounts, however it can't contract with normal accounts. This account can be used to test and config the bot before going live.

You can create one in [here](https://www.facebook.com/whitehat/accounts/).
