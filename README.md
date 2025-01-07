## Status Checker Userbot
check your bot status automatically using userbot, simply and easy.

## Mandatory Vars
1. `API_ID` : Telegram API_ID, get it from my.telegram.org/apps
2. `API_HASH` : Telegram API_ID, get it from my.telegram.org/apps
3. `SESSION_NAME` : A pyrogram session string
4. `BOT_LIST` : Your bot username list without "@" its For public bots status
5. `BOT_LIST1` : your bot username list without "@" its for private bot status 
6. `CHANNEL_OR_GROUP_ID` : Your channel's or group's Telegram id 
7. `MESSAGE_ID` : Telegram id of message from your channel or group (Example: 10)
8. `BOT_ADMIN_IDS` : Bot admin id (Example: 123456 127890) ~ optional
9. `TIME_ZONE`: Your time zone (Example: Asia/Kolkata)

### Deploy To Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/SPARKBRO/status-checker-bot)


### Generate Session String 

Run the following command in your terminal (copy and paste in one go):

```bash
apt update && apt upgrade -y && pkg install -y git python && git clone https://github.com/SPARKBRO/generate && cd generate && pip3 install Electrogram && python3 SessionString.py
