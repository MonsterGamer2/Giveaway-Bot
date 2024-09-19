# GiveawayBot™
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)

### A Discord Giveaway bot written in Discord.js to create & enjoy Feature rich and Seamless Giveaways within your very own Discord guild!

## Links
- ### This Giveaway Bot Was Created by [SurVival_MoNster](https://youtube.com/@survival_monster?si=hfeHm0ChhGCLjQl_)
- [Youtube Channel](https://youtube.com/@survival_monster?si=hfeHm0ChhGCLjQl_))
- [Support Server Link](https://discord.com/invite/xyHqgXZ3RT)

#### Copyright 2021 © All Rights are Reserved 

# Contributions

All contributions are welcomed, it is recommended to create an issue or reply in a comment of an existing issue to let us know what you are working on first, that way we do not overwrite each other.

- Please read [contributing guide](.github/CONTRIBUTING.md) for details on this project.
- Please respect the [pull request template](.github/PULL_REQUEST_TEMPLATE/pull_request_template.md) while submiting a pull request.

# Code of Conduct

Please read [code of conduct](.github/CODE_OF_CONDUCT.md) for details on our code of conduct.

[![forthebadge](https://forthebadge.com/images/badges/it-works-why.svg)](https://forthebadge.com)

# You can run the bot in just a few steps! Let me show you how:
## Hosting 
> ⚠  This bot needs a [Node.js v16.9+](https://nodejs.org/en/blog/release/v16.9.0/)  runtime to function since discord.js version 14 requires said node version to function.

**Aliter**

### Step 1: Install the Dependencies:
Linux 
```sh
wget https://nodejs.org/dist/v16.18.0/node-v16.18.0-linux-x64.tar.xz
unxz node-v16.18.0-linux-x64.tar.xz
tar xvf node-v16.18.0-linux-x64.tar
mv node-v16.18.0-linux-x64 /usr/local/node

ln /usr/local/node/bin/node /usr/bin
ln /usr/local/node/bin/corepack /usr/bin
ln /usr/local/node/bin/npm /usr/bin

corepack enable
```
Windows 
```sh
# https://nodejs.org/en/blog/release/v16.9.1/ get node.js
npm install 
```

### Step 2: Obtain a Bot Token From [Here](https://discord.com/developers) <br> <br>
### Step 3 : Replace the Token in config.json <br>
#### That's all! We Are Done! Now Simply host the Bot!

### Run with node
```sh
node index.js
```
### Run with pm2
```sh
npm install -g pm2@latest
pm2 start --name "Giveaway" index.js --watch
```

# Features
## Featuring | Slash Commands  
### Interactive Giveaway Creation
### Featured ✨ Bonus Entries   
### And Lots More!
- Direct message when the server mentioned for joining is not joined
- Direct message when the server mentioned for joining is joined 
- Direct Message When User Reacts on an ended giveaway
- Direct Message User On Removing Reaction
- Direct Message Winner On Winning
