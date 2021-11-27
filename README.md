# YAGPDB-PokeNav-Badges
This is a reaction custom command for the [YAGPDB bot](https://yagpdb.xyz/). It was developed for the [Rocket Raiders Discord server](https://discord.gg/WsrJUcNETG), that hosts Pokémon GO remote raids across the world. We use the [PokeNav bot](https://pokenavbot.com/) to grant badges for raiders when they have caught a hundo, shiny or shundo legendary raid boss from a raid hosted on our server. This script allows badge moderators to trigger YAGPDB by reacting to a message with the emoji linked to the PokeNav badge.

![YAG Leaderboard](https://i.imgur.com/AmL25m7.png)

This was developed for the specific use of our server and relies on some of the details of how our channels are structured and specific emojis/images that we use. There are elements that you will need to set up, specific for your server. Most of these at the top of the script, but there is one in the body of the script that you will need to adapt to match your own setup.

## How to use these files
You will need to have some understanding of YAGPDB's Custom Commands feature in the Control Panel. If you are not familiar, it will be helpful to read about it [here](https://docs.yagpdb.xyz/commands/custom-commands).

The .yag file in this repository is an individual custom command. You will need to copy/paste the code into the "response" section of the custom command. You will need to set the trigger to *reaction* for it to function correctly.

![YAG Custom Commands—Reaction Trigger](https://i.imgur.com/vcTWab3.png)

## Use at your own risk!
Full disclosure: this is my first significant project, diving into custom commands and using YAGPDB's templating language. While it has been tested and seems to work fine, it comes with no guarantee that it will work perfectly for you.

If you are a serious YAGPDB coder, be gentle with me—I am just learning! Seriously, I would be interested in learning better ways of doing things so feel free to leave me a comment or pull-request.
