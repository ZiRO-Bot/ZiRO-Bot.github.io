# Configuration

!!! info
    `>wizard` command will be added in the future to make it easier for user to setup ziBot.

ziBot is designed to be as customizable as possible.

## Prefixes

By default ziBot's prefix is set to `>`, but you can add and remove prefix by using `>prefix` command:

!!! warning
    You can only add up to 15 prefixes to ziBot!

!!! tips
    Use quotation mark (`"`) to add spaces to the prefix like `"ziBot "` (`"ziBot[space]"`).

* `>prefix add [*prefixes]` - To add prefix <br/>
    Example: `>prefix add !` | `>prefix add "ziBot "`
* `>prefix remove [*prefixes]` - To remove an existing prefix <br/>
    Example: `>prefix remove !` | `>prefix remove "ziBot "`
* `>prefix list` - To get list of existing prefixes

## Welcome and Farewell

To enable Welcome and Farewell messages, all you got to do is create/set channel for greetings:

* `>channel create greeting [channel_name]` - To create channel for greeting <br/>
    Example: `>channel create greeting welcome`
* `>channel set greeting [channel_name]` - To set channel type to greeting <br/>
    Example: `>channel set greeting welcome` | `>channel set greeting #welcome`

You can also set custom Welcome and Farewell messages,

!!! info
    By default, farewell message is not set meaning it will not send farewell messages when a member leaves.

!!! tips
    ziBot supports a "special variables" such as:

    `{mention}` = Mention the new member

* `>settings welcome [message]` - To set welcome message <br/>
    Example: `>settings welcome {mention} has joined the server!`
* `>settings farewell [message]` - To set farewell message <br/>
    Example: `>settings farewell {mention} left the server!`

