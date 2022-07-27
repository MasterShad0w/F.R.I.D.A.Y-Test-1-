<h1 align="center">
𝙁.𝙍.𝙄.𝘿.𝘼.𝙔
</h1>

![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=welcome+To+FRIDAY's+Repo!;A+simple+Group+modular+bot!;and+all+futures!)

<p align="center">
<img src="https://telegra.ph/file/f94c840f80c54492f6d8c.jpg" width ="500">
</p>

<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg" width ="250">
  </a>
  <a href="https://t.me/ShadowKing9o">
    <img src="https://telegra.ph/file/93a7e33b65dc93349c0be.jpg" width="250">
  </a><br>
  <a href="https://t.me/ShadowsArena">
    <img src="https://img.shields.io/badge/Shadow%20Arena-Channel-blue?style=plastic&logo=Telegram" width="130" height="18">
  </a>
  <a href="https://t.me/+9Zhp_GdQVctiNjc1">
    <img src="https://img.shields.io/badge/Movie%20Addaa-Group-blue?style=plastic&logo=Telegram" width="130" height="18">
  </a>
  <br>
  <a href="https://github.com/MasterShad0w/F.R.I.D.A.Y/stargazers">
    <img src="https://img.shields.io/github/stars/MasterShad0w/F.R.I.D.A.Y?style=social">
  </a>
  <a href="https://github.com/MasterShad0w/F.R.I.D.A.Y/fork">
    <img src="https://img.shields.io/github/forks/MasterShad0w/F.R.I.D.A.Y?label=Fork&style=social">
  </a>  
  <br>
  <a href="https://youtube.com/channel/UCqVIzF-2AhO_pY4uo8Rr5Hg">
    <img src="https://img.shields.io/badge/Subscribe-Shadow%20Arena-%23FA0606?style=for-the-badge&logo=Youtube" width="300">
  </a>
</p>

# Features

- [x] ғᴜʟʟ ᴀᴅᴍɪɴ ᴄᴏᴍᴍᴀɴᴅs. 
- [x] ᴍᴏʀᴇ ᴛʜᴀɴ 𝟻𝟶𝟶𝟶 ғɪʟᴛᴇʀs ᴄᴀɴ ʙᴇ sᴇᴛ ᴀᴛ ᴀ ᴛɪᴍᴇ. 
- [x] ᴄᴜsᴛᴏᴍɪᴢᴀʙʟᴇ ɢʀᴇᴇᴛɪɴɢs ᴍᴇssᴀɢᴇs. 
- [x] sᴛɪᴄᴋᴇʀ ᴛᴏ ᴘʜᴏᴛᴏ ᴄᴏɴᴠᴇʀᴛᴇʀ. 
- [x] sᴛᴀᴛs, ᴜsᴇʀs, ᴄʜᴀᴛs, ʙᴀɴ, ᴜɴʙᴀɴ, ʟᴇᴀᴠᴇ, ᴅɪsᴀʙʟᴇ, ᴄʜᴀɴɴᴇʟ
- [x] ᴀɴᴛɪ-ᴄᴏᴍᴍᴀɴᴅ ғᴇᴀᴛᴜʀᴇ ᴛᴏ ᴀᴠᴏɪᴅ ᴜɴᴡᴀɴᴛᴇᴅ ᴄᴏᴍᴍᴀɴᴅ ᴍᴇssᴀɢᴇs. 
- [x] ʟᴏɢ ᴄʜᴀɴɴᴇʟ ғᴏʀ ᴀʟʟ ᴛʏᴘᴇ ᴏғ ʟᴏɢs. 
- [x] ᴀɴᴛɪ-ғʟᴏᴏᴅ ᴛᴏ ᴀᴠᴏɪᴅ sᴘᴀᴍᴍᴇʀs .
- [x] ɪᴅ's ᴀɴᴅ ᴜsᴇʀ's ɪɴғᴏ. 
- [x] 𝟸𝟺×𝟽 sᴜᴘᴘᴏʀᴛ sᴇʀᴠɪᴄᴇ . <br>

𝘼𝙣𝙙 𝙈𝙖𝙣𝙮 𝙢𝙤𝙧𝙚.....

## Deploy
𝙀𝙖𝙨𝙞𝙚𝙨𝙩 𝙬𝙖𝙮, 𝙩𝙝𝙚 𝙃𝙚𝙧𝙤𝙠𝙪👇👇

<details><summary>Deploy to Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/MasterShad0w/F.R.I.D.A.Y">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</p>
</details>


## Starting the bot.

Once you've setup your database and your configuration (see below) is complete, simply run:

`python3 -m tg_bot`


## Setting up the bot (Read this before trying to use!):
Please make sure to use python3.6, as I cannot guarantee everything will work as expected on older python versions!
This is because markdown parsing is done by iterating through a dict, which are ordered by default in 3.6.

### Configuration

There are two possible ways of configuring your bot: a config.py file, or ENV variables.

The prefered version is to use a `config.py` file, as it makes it easier to see all your settings grouped together.
This file should be placed in your `tg_bot` folder, alongside the `__main__.py` file . 
This is where your bot token will be loaded from, as well as your database URI (if you're using a database), and most of 
your other settings.

It is recommended to import sample_config and extend the Config class, as this will ensure your config contains all 
defaults set in the sample_config, hence making it easier to upgrade.

An example `config.py` file could be:
```
from tg_bot.sample_config import Config


class Development(Config):
    OWNER_ID = 1096707867  # my telegram ID
    OWNER_USERNAME = "ShadowKing9o"  # my telegram username
    API_KEY = "your bot api key"  # my api key, as provided by the botfather
    SQLALCHEMY_DATABASE_URI = 'postgresql://username:password@localhost:5432/database'  # sample db credentials
    MESSAGE_DUMP = '-1234567890' # some group chat that your bot is a member of
    USE_MESSAGE_DUMP = True
    SUDO_USERS = [1096707867]  # List of id's for users which have sudo access to the bot.
    LOAD = []
    NO_LOAD = ['translation']
```

If you can't have a config.py file (EG on heroku), it is also possible to use environment variables.
The following env variables are supported:
 - `ENV`: Setting this to ANYTHING will enable env variables

 - `TOKEN`: Your bot token, as a string.
 - `OWNER_ID`: An integer of consisting of your owner ID
 - `OWNER_USERNAME`: Your username

 - `DATABASE_URL`: Your database URL
 - `MESSAGE_DUMP`: optional: a chat where your replied saved messages are stored, to stop people deleting their old 
 - `LOAD`: Space separated list of modules you would like to load
 - `NO_LOAD`: Space separated list of modules you would like NOT to load
 - `WEBHOOK`: Setting this to ANYTHING will enable webhooks when in env mode
 messages
 - `URL`: The URL your webhook should connect to (only needed for webhook mode)
 - `BMERNU_SCUT_SRELFTI`: No. of custom filters which can be set in each group

 - `SUDO_USERS`: A space separated list of user_ids which should be considered sudo users
 - `SUPPORT_USERS`: A space separated list of user_ids which should be considered support users (can gban/ungban,
 nothing else)
 - `WHITELIST_USERS`: A space separated list of user_ids which should be considered whitelisted - they can't be banned.
 - `DONATION_LINK`: Optional: link where you would like to receive donations.
 - `CERT_PATH`: Path to your webhook certificate
 - `PORT`: Port to use for your webhooks
 - `DEL_CMDS`: Whether to delete commands from users which don't have rights to use that command
 - `STRICT_GBAN`: Enforce gbans across new groups as well as old groups. When a gbanned user talks, he will be banned.
 - `WORKERS`: Number of threads to use. 8 is the recommended (and default) amount, but your experience may vary.
 __Note__ that going crazy with more threads wont necessarily speed up your bot, given the large amount of sql data 
 accesses, and the way python asynchronous calls work.
 - `BAN_STICKER`: Which sticker to use when banning people.
 - `ALLOW_EXCL`: Whether to allow using exclamation marks ! for commands as well as /.

### Python dependencies

Install the necessary python dependencies by moving to the project directory and running:

`pip3 install -r requirements.txt`.

This will install all necessary python packages.

### Database

If you wish to use a database-dependent module (eg: locks, notes, userinfo, users, filters, welcomes),
you'll need to have a database installed on your system. I use postgres, so I recommend using it for optimal compatibility.

In the case of postgres, this is how you would set up a the database on a debian/ubuntu system. Other distributions may vary.

- install postgresql:

`sudo apt-get update && sudo apt-get install postgresql`

- change to the postgres user:

`sudo su - postgres`

- create a new database user (change YOUR_USER appropriately):

`createuser -P -s -e YOUR_USER`

This will be followed by you needing to input your password.

- create a new database table:

`createdb -O YOUR_USER YOUR_DB_NAME`

Change YOUR_USER and YOUR_DB_NAME appropriately.

- finally:

`psql YOUR_DB_NAME -h YOUR_HOST YOUR_USER`

This will allow you to connect to your database via your terminal.
By default, YOUR_HOST should be 0.0.0.0:5432.

You should now be able to build your database URI. This will be:

`sqldbtype://username:pw@hostname:port/db_name`

Replace sqldbtype with whichever db youre using (eg postgres, mysql, sqllite, etc)
repeat for your username, password, hostname (localhost?), port (5432?), and db name.

## Support

[![telegram badge](https://img.shields.io/badge/Telegram-Group-30302f?style=flat&logo=telegram)](https://t.me/+9Zhp_GdQVctiNjc1)
[![telegram badge](https://img.shields.io/badge/Telegram-Channel-30302f?style=flat&logo=telegram)](https://t.me/ShadowsArena) 

## Disclaimer
[![GNU Affero General Public License 3.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL 3.0.](https://github.com/MasterShad0w/F.R.I.D.A.Y/blob/master/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.
