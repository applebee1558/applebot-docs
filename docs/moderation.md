# Moderation Module
The moderation module has many commands that can help you with moderating your server. 

!!! danger "Warning"
    As of 6/15/2020, this module has changed a LOT and this documentation is outdated. This message will be removed once I update these docs.
    As of 07/02/2021, this documentation is even more severely outdated. Please do not read this until someone fixes it.

!!! note "Note" 
    Replace [prefix] with the prefix that the bot is set to in your server. If you forgot your prefix, just mention the bot to get the prefix set.

## Ban
Usage: `[prefix]ban <user> [delete_message_days] [reason]`

Bans the user specified in the user parameter, purging messages according to the delete_message_days paramater and with a reason of the reason paramater. This command will DM the user the ban reason and moderator. You can also pass IDs into the user paramater if the user is not in your server. This will "hackban" that user from your server. 

## Bans
Usage: `[prefix]bans`

Shows all the bans in the server with the ban reason.

## Kick
Usage: `[prefix]kick <user> [reason]`

Kicks the user from the server with the reason specified in the reason paramater.

## Voice Channel Kick
Usage: `[prefix]vckick <user>`

Kicks `<user>` from the current voice channel that they are within.

## Mute
Usage: `[prefix]mute <user> [time] [reason]`

Gives the user the muterole set with `[prefix]set edit muterole <role>` for the duration time (which is in seconds) and an optional reason that gets logged. This command will turn the mute to a permanent mute if the user leaves the server and tries to evade the role.

## Mutes
Usage: `[prefix]mutes`

Shows all the muted users in the server.

## Purge
Usage: `[prefix]purge <amount>`

Deletes `<amount>` number of messages from the current channel.
!!! danger "Warning"
    If you put a huge amount of messages, the bot **WILL** purge that amount of messages. Please be careful and don't make decisions that you would regret later.

## Prune
Usage: `[prefix]prune <member> <amount>`

Searches [amount] messages in the channel this command is executed in and deletes all the messages that match the member. 

## Role
Usage: `[prefix]role <user> [role]`

Givers or removes `[role]` from `<user>` relative to whether or not they have the role.

## Words
Usage: `[prefix]words <add/clear/delete> [banned word]`

Adds or removes `[banned word]` from the banned words list. Messages that contain banned words will me automatically deleted from channels the bot has access to. `<.../clear/...>` will clear the banned words list.

## Purge
Usage: `[purge] <amount>`

Purges the [amount] of messages from the channel this command is executed in. 

## Record
Usage: `[prefix]record <start/stop/purge>`

Start: Starts a recording in the channel
Stop: Stops current recording
Purge: Purges all the messages in the recording. This is all the messages between your `record start` and `record stop`

## Role
Usage `[prefix]role <member> <role>`

Toggles the role from the member. If the user has the role, the role will be removed from the target. If the target does not have this role, it would be added to the target.

## Temp Role
Usage: `[prefix]temprole <member> <time> <role>`

Gives `[member]` the `[role]` for x amount of time in seconds.
