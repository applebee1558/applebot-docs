# Music Module
This module includes many commands that can help you play music in a Voice Channel. Commands here can be used by anyone, but if the server has the dj_only setting enabled, users must have the role set in the dj_role in order to use music commands when there's more than one person in the voice channel. The play command is the only exception to this rule. When the user is alone with the bot though, they can use all the music commands they want.

!!! note "Info" 
    Having a dj_role set without dj_only enabled will give members with that role the ability to use commands without being in the Voice Channel. You can set the dj role by doing `[prefix]set edit dj_role <role>`

!!! note "Note" 
    Replace [prefix] with the prefix that the bot is set to in your server. If you forgot your prefix, just mention the bot to get the prefix set for your server.

## Play
Usage: `[prefix]play <query>`

Plays a song from the given query. If another song is currently playing, the song would be added to the end of the query.
For the query field, you can pass keywords and it will default to youtube searching. If you pass a url or a search query, it would query that instead.
Valid queries are `ytsearch: song name`(searches youtube) and `scearch: song name`(for soundcloud)

!!! note "Note" 
    There are many other supported sources such as twich and bandcamp, but you must paste the link instead of searching.
## Now Playing
Usage: `[prefix][np|now_playing]

Shows the status of the current song playing. The round icon would be a pause icon if the current queue is paused.

## View Queue
Usage: `[prefix][queue]`

Shows the current pending queue, and a embed paginator if there is too much songs to fit in one page.

## Skip
Usage: `[prefix][skip]`

Skips the current song and plays the next one in the queue.

## Pause
Usage: `[prefix][pause]`

Pauses the current queue until the `resume` command is used.
