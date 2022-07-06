<script type="text/javascript" src="https://cdn.applebee1558.com/applebot-docs-assets/coloris.min.js"></script>
<link rel="stylesheet" type="text/css" href="https://cdn.applebee1558.com/applebot-docs-assets/coloris.min.css"></link>
<style>
    .circle .clr-field button {
        border-radius: 50%;
        width: 22px;
        height: 22px;
        right: 20px;
    }
    
    input {
      width: 150px;
      height: 32px;
      padding: 0 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-family: inherit;
      font-size: inherit;
      font-weight: inherit;
      box-sizing: border-box;
    }
</style>

# Ticket Module
This module allows you to use private channels as an in-app ticketing system for Discord. Use `[prefix] ticket setup` to get started!

!!! note "Note" 
    All commands in this module begin with `[prefix] ticket`
## Send Button
Usage: `[prefix]ticket send_button <channel>`

Sends the message with a button that can be used for ticket creation. Pass the channel you want in the channel paramater. This message can be set using the command `[prefix] ticket set_creation_embed`

## Set Creation Embed
Usage: `[prefix] ticket set_creation_embed`

Sets the message embed shown for the ticket creation message. This starts an interactive embed builder to fill out the prompts. 

## Set Greet Embed
Usage: `[prefix] ticket set_greet_embed`

Sets the message embed shown for the first message that's sent when a ticket is opened. This starts an interactive embed builder to fill out the prompts. 

## Custom Color Hex Code Generator
<div class="example circle">
    <input type="text" class="coloris" value="#ffcc00">
</div>
<script type="text/javascript">

    Coloris({
      el: '.coloris',
      swatches: [
        '#264653',
        '#2a9d8f',
        '#e9c46a',
        '#f4a261',
        '#e76f51',
        '#d62828',
        '#023e8a',
        '#0077b6',
        '#0096c7',
        '#00b4d8',
        '#48cae4'
      ]
    });

</script>
