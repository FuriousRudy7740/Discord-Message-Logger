# Discord-Message-Logger
A discord bot written in Node.js to log all sent messages to a txt file that can be called using the bots built in functions. 

Setting up the bot is fairly simple, all you have to do is create a application on the page https://discord.com/developers/applications and within that application make a bot then copy its token. once you have the token you will have to input it into the config.json file where it is defined.

The bot is simple, run the code in a terminal with the command (node bot.js > log-file.txt) be aware that doing so resets the txt file.
commands use the prefix = and are as follows, help displays this paragraph, status doesnt return anything if the bot isnt working like all the other commands, and current sends the txt file to the channel
