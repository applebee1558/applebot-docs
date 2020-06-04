# Moderation Module
The moderation module has many commands that can help you with moderating your server. All commands in this module currently require you to have the 
`ADMINISTRATOR` permission in order to use it. This will be customizable and changable in the future.

!!! note "Note" 
    Replace [prefix] with the prefix that the bot is set to in your server. If you forgot your prefix, just mention the bot to get the prefix set.

## Ban
Usage: `[prefix]ban <user> [delete_message_days] [reason]`

Bans the user specified in the user parameter, purging messages according to the delete_message_days paramater and with a reason of the reason paramater. This command will DM the user the ban reason and moderator. You can also pass IDs into the user paramater if the user is not in your server. This will "hackban" that user from your server. 

## Kick
Usage: `[prefix]kick <user> [reason]`

Kicks the user from the server with the reason specified in the reason paramater.

## Mute
Usage: `[prefix]mute <user> [time] [reason]`

Gives the user the muterole set with `[prefix]set edit muterole <role>` for the duration time (which is in seconds) and an optional reason that gets logged. This command will turn the mute to a permanent mute if the user leaves the server and tries to evade the role.