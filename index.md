# Cheesy Pasta Bot
![Logo](https://i.redd.it/up0qtlxowbf81.png)

## About
A discord bot written in [discordJS](https://github.com/discordjs/discord.js/) and using [nodeJS](https://nodejs.org/en/) that provides images via [reddit](https://www.redditinc.com/). This bot was created for entertainment purposes, though as of now, this bot is not online on discord's platform. However, the source code will still be updated often.

Unlike the old ["CheeseAndPastaBot"](https://github.com/CheeseAndPastaResp/CheeseAndPastaBot/) that I made about two years ago, this isn't as crappy as it was before. As of now, the bot will be maintained for personal entertainment reasons and some educational/school reasons. If you want more detail into why this is still being maintained and why it is being revamped go [here](https://github.com/StackUnderflow1617/CheesyPastaBot/blob/other/REVAMPING.md).

## Installation

This section is for people that aren't too familiar with nodeJS and node modules as a whole. While the bot source code is already there and ready, the node modules aren't. Install a program like [VSCode](https://code.visualstudio.com/) to get started.

Now, clone the source code [here](https://codeload.github.com/StackUnderflow1617/CheesyPastaBot/zip/refs/heads/main) and extract the contents from the folder. Once you have done that open the folder in VSCode and press (CTRL + `) to open up the terminal.

Now just before you put anything into the terminal, make sure you have downloaded [nodeJS](https://nodejs.org/dist/v17.4.0/node-v17.4.0-x64.msi) since it is the program we use to download the modules. Once you have fully installed it, go back into VSCode and type in `npm install discord.js`.

If you are unsure of what should be happening, go into the folder after a while there should be a `node_modules` folder that contains all the modules needed for it to **properly** run. Just to be sure, go into the ./package.json and look at the dependencies, this will tell what is needed. To install these modules (again or not) just do `npm install (name_of_module)` and it will install.

After this, the node modules should have installed.

To then run the bot, go into the terminal and run ```node index.js``` and the program should say "This bot is online!"

Make sure you know how to get your own bot and oauth2 stuff ready.

### Dependencies 
- [DiscordJS](https://github.com/discordjs/discord.js/) ```npm i discord.js```
- [imageAPI.js](https://github.com/Milo123459/imageapi.js) ```npm i imageapi.js```
- [ms](https://github.com/vercel/ms) ```npm i ms```
- [random-puppy](https://github.com/dylang/random-puppy) ```npm i random-puppy```

### Optional Downloads/Alternatives

- [VSCodium](https://vscodium.com/) (Alternative)
- [Git](https://git-scm.com/downloads) (Optional)
- [Yarn](https://classic.yarnpkg.com/lang/en/) (Alternative)
- [pnpm](https://github.com/pnpm/pnpm/releases/tag/v6.29.1) (Alternative)
- [Github CLI](https://cli.github.com/) (Optional)
- [Notepad++](https://notepad-plus-plus.org/downloads/) (Optional)

## Features

- Get cat images from 280+ subreddits!
- Get dog images from 100+ subreddits!
- Get food images from 70+ subreddits!
- Do basic moderation features like banning and kicking.
- and etc~!

## Notes
- Search things up if you don't understand stuff. Thanks :)
