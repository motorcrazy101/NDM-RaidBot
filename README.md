# Douchebag MODE Discord Server Bot/Nuke Bot
## Made by SelfCenteredDouchebag
NDM-RaidBot is currently the **FASTEST** and **FREE** self-hosted nuke bot out here. All commands will be focused on nuking-related.

Issues are closed because we are not active in there. Join our discord if you need help, see plans for the future updates, suggestions, or beta testing a newer version of the bot: [https://discord.gg/anime-asylum]

[All 51 commands](manual.md)

```
[addRole] [addChannel] [autoNick] [addVoiceChannel] [autoStatus] 
[addEmoji] [addCategory] [banAll] [bans] [ban] [channelBomb] 
[categoryBomb] [config] [checkRolePermissions] [connect] [categories] 
[changeStatus] [channels] [deleteRole] [deleteChannel] 
[deleteVoiceChannel] [deleteCategory] [deleteCC] [deleteEmoji] 
[deleteAllRoles] [deleteAllChannels] [disableCommunityMode] 
[deleteAllEmojis] [deleteAllWebhooks] [emojis] [grantAllPerm] 
[help] [joinNuke] [kaboom] [leave] [leaveAll] [link] [moveRole] 
[members] [nuke] [off] [purge] [roles] [roleBomb] [roleTo] [servers] 
[serverIcon] [serverName] [unban] [voiceChannels] [webhook] 
```

# IMPORTANT: 
* We will not take any responsibility over whatever you are going to do with this bot.
* The bot will still have to obey the [server limitings](https://discordia.me/en/server-limits) because of that in discord, there are rate limitings. You will see a lot of rate limiting in the console while using some commands. (because the bot is too fast on creating or deleting.)
* Also, since we are using HTTP requests, unlike other nuke bot out there, DoucheBag spam creating channel, role, and category(CRC) can create beyond the 250 limit for CRC that the old nuking bots have.

## Messages

* Keep it Douchey!

## Why did my computer say it's a dangerous file/containing virus?
* I'm going to make myself clear here - it's not a virus.

## Main Usage (Please read `.config` command below before contacting me)
`.nuke <true or false>` - It's a combination of a few commands: `.deleteAllChannels`, `.deleteAllEmojis`, `.deleteAllRoles`, `.banAll`, and `.deleteAllWebhooks`. True or false is an optional argument that is set to true by default and used for disabling after commands. (This command doesn't need to be configed with `.config`, Note: you can also use all the commands listed above seperately)
* `.kaboom <#of bombs> <wordlist>` - Mass create text channels, roles, and categories(CRC). Number of bombs is just how many CRCs you want to spam create. There are 3 word lists, 2 built in, and 1 from user inputs: `fixed` - random text chosen from user inputs, `b64` - random base64 characters, `an` -  random alphanumeral characters. (Use `.config bomb_messages <args...>` to see how to set up the bomb commands)
* `.check <userID|tag,|ping>` - Checks for the permissions that the bot has in a server.
* `.autoNick` - Nicks the bot itselfs every few moments to bounce around the member list, making it harder for admins to kick the bot.
* `.autoStatus` - changes from online to offline and offline to online every few moments to bounce around the member list.
* `.config <feature> <args...>` - if you just type out `.config` it will show you all the features that you can config and it will guide you with text in the `.config` command. For example, if you want to add webhook spammer names to config webhook spam, you first want to type `.config webhook_spam`. The bot will send out a description of the webhook_spam feature and the config commands you can use to config the webhook_spam feature. From there you should be able to find something like `webhook <type> add <text>` for adding something into the `<type>` in this case you want to choose the username for the spammers, so you can type `.config webhook_spam usernames add Douchebag` for adding usernames to  webhook_spam.

## Guides
### 2.4 setup
* Run the .exe
* You will see the "Enter token" message. You can only enter a bot token because selfbot is no longer supported.
* Next you will see "Enter user ID or tag", you should enter the user ID or tag that you wanted to command the bot with. All command permissions will be granted to the user with the ID or tag you entered here.
* If you want to know what commmands are there, then run `.help`
* If you want to config any settings like the after commands or the webhook spam commands, you have to use `.config`. For more information on how to config will be in the `.config` command.
* If you are having problems, feel free to create a Support Ticket in our discord server here: (https://discord.gg/anime-asylum).
