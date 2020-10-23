!!! info
    ```
    () means requires arguments
    [] means optional arguments
    |  means seperator
    ```

## General

| Name  | Aliases                             | Description                                                  | Usage   | Example |
|-------|-------------------------------------|--------------------------------------------------------------|---------|---------|
|botinfo| bi\|about\|info\|uptime\|up\|invite | Show bot information. (such as uptime, invitation link, etc) | botinfo |         |
|ping   | p                                   | Tell the ping of the bot to the discord servers.             | ping    |         |
|       |                                     |                                                              |         |         |
|       |                                     |                                                              |         |         |

## AniList

| Name      | Aliases | Description                                    | Usage                       | Example                           |
|-----------|---------|------------------------------------------------|-----------------------------|-----------------------------------|
|anime info |         | Get information about an anime.                | anime info (anime) [format] | anime info "Koe no Katachi" Movie |

## Custom Commands

!!! info
    By default Custom Commands only available for server staff with manage server permission. You can disable it by using `>settings mods_only (commands)`

    Custom Commands support special value called "tags" such as `{server}` and `{user}`. <br/>
    Go to **Advanced Usage** for more information!

| Name         | Aliases                     | Description             | Usage                                   | Example                                  |
|--------------|-----------------------------|-------------------------|-----------------------------------------|------------------------------------------|
|command add   | command\|tag\|cmd +\|create | Add new custom command  | command add (name) (content/message)    | command add someone \{server(random)\}   |
|command edit  | command\|tag\|cmd ed\|&     | Edit a custom command   | command ed (name) (new content/message) | command ed someone Hi \{server(random)\}!|
|command remove| command\|tag\|cmd rm\|-     | Remove a custom command | command rm (name)                       | command rm someone                       |

## Auto Response

Coming soon.
