# Getting Started
!!! tips
    Hosting ziBot on your own server is recommended!

## User (Limited Control)
* [Invite ziBot](https://discord.com/oauth2/authorize?client_id=740122842988937286&scope=bot&permissions=2080898294) to your server
* Configure ziBot with `>settings` and `>prefix`

## Host (Full Control)

!!! warning
    You need atleast Python 3.8 or later to host the bot!

* Clone the repository:
```zsh
git clone https://github.com/ZiRO-Bot/ziBot.git
```

* Install the dependencies, by using the following command:
```zsh
# Linux
python3 -m pip install -r requirements.txt

# Windows
py -3 -m pip install -r requirements.txt
```
* Create a file named `config.json` with this format:

!!! hint
    Replace `YOUR-TOKEN-HERE` with your bot's token!
```json
{
    "bot_token": "YOUR-TOKEN-HERE",
    "twitch": {
        "id": "",
        "secret": ""
    },
    "reddit": {
        "id": "",
        "secret": "",
        "user_agent": "ziBot/0.4"
    },
    "openweather_apikey": ""
}
```

* Launch the bot with this command: 
``` zsh
# Linux
python3 zibot.py

# Windows
py -3 zibot.py
```

If nothing went wrong, your bot should be up and running.
