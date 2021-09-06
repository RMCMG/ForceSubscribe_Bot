# Force Subscribe Bot
Forces a user to join your group/channel so as to be able to message in a group.

# Features
- Checks for all newly joined members with a customisable welcome message.
- Checks for users who are already in the group but has not joined the channel.

# Variables
- `API_ID` - Your telegram api id from my.telegram.org
- `API_HASH` - Your telegram api hash from my.telegram.org
- `BOT_TOKEN` - Your telegram bot token.
- `CHANNEL` - Username of the channel/group where users must join.
- `WELCOME_MSG` - The welcome message you want.
`WELCOME_NOT_JOINED` - Welcome message to show if user is not in the channel.
- `ON_JOIN` - True/False - Set as True if the user must be muted, if not in Channel/group, directly when he joins.
- `ON_NEW_MSG` - True/False - Set as True if the user must be muted, if not in Channel/group, on sending a message.

Note: `WELCOME_MSG` and `WELCOME_NOT_JOINED` can both be formatted using parameters like `{mention}`, `{title}`, `{fullname}`, `{username}`, `{name}`, `{last}`, `{channel}`

# Deploy to heroku
[![Deploy](https://img.shields.io/badge/Deploy%20To-Heroku-blueviolet)](https://dashboard.heroku.com/new?button-url=android-app%3A%2F%2Forg.telegram.messenger%2F&template=https%3A%2F%2Fgithub.com%2FRMCMG%2FForceSubscribe_Bot)

# Deploy locally
- `git clone https://github.com/xditya/ForceSub`
- `cd ForceSub`
- `pip3 install -U -r requirements.txt`
- `touch .env`,  `nano .env` and fill in the [vars](.env.sample), Ctrl+S, Ctrl+X
- Run the bot, `python3 bot.py`

# Credits
<a href="https://t.me/mkspali"> <img src="https://img.shields.io/badge/This%20Bot%20Was-Made%20By%20My-orange" /> <img src="https://img.shields.io/badge/Bestest-Master-ff69b4" /> </a>
