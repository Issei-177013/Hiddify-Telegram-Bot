<p align="center">
  <a href="https://github.com/B3H1Z/Hiddify-Telegram-Bot" target="_blank" rel="noopener noreferrer">
    <img width="200" height="200" src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/icon.png?raw=True" alt="Hidy Bot">
  </a>
</p>

<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README-FA.md">فارسی</a>
</p>

<h1 align="center">Hidy Bot</h1>

Hidy Bot is a Telegram bot that allows you to manage your Hiddify panel directly from Telegram.

Install Hidy Bot on the **SAME SERVER** as your Hiddify panel.

**Please note:** This project is currently in BETA, and we are actively working to make it even better. If you encounter any bugs or issues, we appreciate your feedback and bug reports.

> Disclaimer: This bot is **not official** and is not affiliated with Hiddify team.

## Features

- [x] Add users
- [x] Remove users
- [x] Edit user details
- [x] View users list
- [x] Search users (by name, configuration, UUID)
- [x] Show user information (name, traffic, date, etc.)
- [x] Display user configs and subscription links
- [x] Get a backup of your panel
- [x] View server status (RAM, CPU, disk)
- [x] and more...

## Installation

To install the bot, run the following command:

```bash
sudo bash -c "$(curl -Lfo- https://raw.githubusercontent.com/B3H1Z/Hiddify-Telegram-Bot/main/install.sh)"
```
<br>

Make sure you have the following information ready:

1. `Admin Telegram Number ID` : Get it from [User info bot](https://t.me/userinfobot) (Example: `123456789`)
2. `Telgram Bot Token` : Get it from [BotFather](https://t.me/BotFather) (
   Example: `1234567890:ABCdEfGhIjKlMnOpQrStUvWxYz`)
3. `Hiddify Panel URL` : The url of your Hiddify panel (
   Example: `https://panel.example.com/7frgemkvtE0/78854985-68dp-425c-989b-7ap0c6kr9bd4`) <b>exactly like this
   pattern!</b>
4. `Bot Language` : Options are `en` and `fa` [default is `fa`]



Now you can use the bot in Telegram by sending the `/start` command.




## Commands
- ### Update bot

      cd /opt/Hiddify-Telegram-Bot/ && chmod +x update.sh && ./update.sh
- ### Restart bot

      cd /opt/Hiddify-Telegram-Bot/ && chmod +x restart.sh && ./restart.sh
- ### Stop bot

      pkill -9 -f hidyBot.py
- ### Get bot logs

      cat /opt/Hiddify-Telegram-Bot/hiddify-telegram-bot.log
- ### Get bot configs

      cat /opt/Hiddify-Telegram-Bot/config.json
- ### Change bot configs

      cd /opt/Hiddify-Telegram-Bot/ && python3 config.py && ./restart.sh
- ### Reinstall bot (if you have any problem with update)

      rm -rf /opt/Hiddify-Telegram-Bot/ && sudo bash -c "$(curl -Lfo- https://raw.githubusercontent.com/B3H1Z/Hiddify-Telegram-Bot/main/install.sh)"
## Screenshots
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/Keyboard.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/UsersList.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/UserInfo.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/EditUser.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/ConfigAndSub.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/Search.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/AddUser.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/BackupAndStartus.PNG?raw=True" width=50% height=50%>