 <p align="center">
  <img src="https://telegra.ph/file/8e1b75d0d633e9eaa0f16.png">
</p>

# Naruto Robot

<p align="center">
- x -|│  “	Just some code who is a bot for fun. ”  │| - x -
</p>

<p align="center">
<a href="https://app.codacy.com/gh/theshashankk/naruto?utm_source=github.com&utm_medium=referral&utm_content=Theshashankk/Naruto&utm_campaign=Badge_Grade_Settings" alt="Codacy Badge">
<img src="https://api.codacy.com/project/badge/Grade/6141417ceaf84545bab6bd671503df51" /> </a>
<a href="https://github.com/theshashankk/Naruto" alt="Libraries.io dependency status for GitHub repo"> <img src="https://img.shields.io/librariesio/github/Theshashankk/Naruto" /> </a>
<a href="http://hits.dwyl.com/theshashankk/naruto" alt="HitCount"> <img src="http://hits.dwyl.com/theshashankk/naruto.svg" /> </a>
</p>
<p align="center">
<a href="https://github.com/theshashankk/naruto" alt="GitHub closed issues"> <img src="https://img.shields.io/github/issues-closed-raw/theshashankk/naruto?style=flat&logo=github&color=success" /> </a>
<a href="https://github.com/theshashankk/naruto" alt="GitHub commit activity"> <img src="https://img.shields.io/github/commit-activity/m/theshashankk/naruto" /> </a>
<a href="https://github.com/theshashankk/naruto/graphs/contributors" alt="GitHub contributors"> <img src="https://img.shields.io/github/contributors/theshashankk/naruto?style=flat&logo=github" /> </a>
<a href="https://github.com/theshashankk/naruto/network/members" alt="GitHub forks"> <img src="https://img.shields.io/github/forks/theshashankk/naruto?label=Forks&logo=github" /> </a>
<a href="https://github.com/theshashankk/naruto" alt="GitHub closed pull requests"> <img src="https://img.shields.io/github/issues-pr-closed-raw/theshashankk/naruto?color=success" /> </a>
<a href="https://github.com/theshashankk/naruto" alt="GitHub issues"> <img src="https://img.shields.io/github/issues-raw/theshashankk/naruto?style=flat&logo=github&color=yellow" /> </a>
</p>
<p align="center">
<a href="https://github.com/theshashankk/naruto" alt="GitHub release (latest by date including pre-releases)"> <img src="https://img.shields.io/github/v/release/theshashankk/naruto?include_prereleases?style=flat&logo=github" /> </a>
<a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=flat&logo=python&color=blue" /> </a>
<a href="https://github.com/theshashankk/naruto" alt="Docker!"> <img src="https://aleen42.github.io/badges/src/docker.svg" /> </a>
<a href="https://github.com/theshashankk/naruto" alt="GitHub repo size"> <img src="https://img.shields.io/github/repo-size/theshashankk/naruto" /> </a>
<a href="https://github.com/theshashankk/naruto/blob/master/LICENSE" alt="GPLv3 license"> <img src="https://img.shields.io/badge/License-GPLv3-blue.svg" /> </a>
</p>
<p align="center">
<a href="https://ko-fi.com/sawada" alt="Donate!"> <img src="https://aleen42.github.io/badges/src/paypal.svg" /> </a>
<a href="https://t.me/Theshashank" alt="Telegram!"> <img src="https://aleen42.github.io/badges/src/telegram.svg" /> </a>
<a href="https://discord.animekaizoku.com" alt="Discord"> <img src="https://img.shields.io/discord/465068856692441090?style=flat&logo=discord&color=blue" /> </a>
<a href="" alt="ShashanK"> <img src="https://img.shields.io/badge/Built%20by-Shashank-blue" /> </a>
<a href="https://github.com/theshashankk/naruto/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" /> </a>
<a href="https://makeapullrequest.com" alt="PRs Welcome"> <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" /> </a>
</p>



Saitama is a simple one-punch solution to your group management needs and has become one of the most prominently kanged bots around telegram, purely weeab themed.

* Bot Link:  <a href="https://t.me/naruto_RooBoT" alt="Naruto Robot"> <img src="https://img.shields.io/badge/%F0%9F%A4%96%20-naruto-blue" /> </a>
* News channel: <a  href="https://t.me/narutosupport" alt="Naruto Updates"> <img  src="https://img.shields.io/badge/%F0%9F%92%A1-20naruto%20Updates-9cf" /> </a>

Should you be forking this repo then do not forget to star it - <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/theshashankk/naruto?color=white&label=%F0%9F%8C%9F%20star">

# Deploy
[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/theshashankk/naruto)
## How to setup/deploy.



<details>
  <summary>Steps to deploy on Heroku !! </summary>

```
Fill in all the details, Deploy!
Now go to https://dashboard.heroku.com/apps/(app-name)/resources ( Replace (app-name) with your app name )
Turn on worker dyno (Don't worry It's free :D) & Webhook
Now send the bot /start, If it doesn't respond go to https://dashboard.heroku.com/apps/(app-name)/settings and remove webhook and port.
```

</details>  
<details>
  <summary>Steps to self Host!! </summary>

  ## Setting up the bot (Read this before trying to use!):
Please make sure to use python3.6, as I cannot guarantee everything will work as expected on older Python versions!
This is because markdown parsing is done by iterating through a dict, which is ordered by default in 3.6.

  ### Configuration

There are two possible ways of configuring your bot: a config.py file, or ENV variables.

The preferred version is to use a `config.py` file, as it makes it easier to see all your settings grouped together.
This file should be placed in your `SaitamaRobot` folder, alongside the `__main__.py` file. 
This is where your bot token will be loaded from, as well as your database URI (if you're using a database), and most of 
your other settings.

It is recommended to import sample_config and extend the Config class, as this will ensure your config contains all 
defaults set in the sample_config, hence making it easier to upgrade.

An example `config.py` file could be:
```
from SaitamaRobot.sample_config import Config

class Development(Config):
    OWNER_ID = 254318997  # your telegram ID
    OWNER_USERNAME = "Theshashank"  # your telegram username
    API_KEY = "your bot api key"  # your api key, as provided by the @botfather
    SQLALCHEMY_DATABASE_URI = 'postgresql://username:password@localhost:5432/database'  # sample db credentials
    MESSAGE_DUMP = '-1234567890' # some group chat that your bot is a member of
    USE_MESSAGE_DUMP = True
    SUDO_USERS = [18673980, 83489514]  # List of id's for users which have sudo access to the bot.
    LOAD = []
    NO_LOAD = ['translation']
```

If you can't have a config.py file (EG on Heroku), it is also possible to use environment variables.
The following env variables are supported:
 - `ENV`: Setting this to ANYTHING will enable env variables

- `TOKEN`: Your bot token, as a string.
 - `OWNER_ID`:  integer of consisting of your owner ID
 - `OWNER_USERNAME`: Your username

 - `DATABASE_URL`: Your database URL
 - `MESSAGE_DUMP`: optional: a chat where your replied saved messages are stored, to stop people deleting their old 
 - `LOAD`: Space-separated list of modules you would like to load
 - `NO_LOAD`: Space-separated list of modules you would like NOT to load
 - `WEBHOOK`: Setting this to ANYTHING will enable webhooks when in env mode
 messages
 - `URL`: The URL your webhook should connect to (only needed for webhook mode)

 - `SUDO_USERS`: A space-separated list of user_ids which should be considered sudo users
 - `SUPPORT_USERS`: A space-separated list of user_ids which should be considered support users (can gban/ungban,
 nothing else)
 - `WHITELIST_USERS`: A space-separated list of user_ids which should be considered whitelisted - they can't be banned.
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

Install the necessary Python dependencies by moving to the project directory and running:

`pip3 install -r requirements.txt`.

This will install all the necessary python packages.

  ### Database

If you wish to use a database-dependent module (eg: locks, notes, userinfo, users, filters, welcomes),
you'll need to have a database installed on your system. I use Postgres, so I recommend using it for optimal compatibility.

In the case of Postgres, this is how you would set up a database on a Debian/ubuntu system. Other distributions may vary.

- install postgresql:

`sudo apt-get update && sudo apt-get install postgresql`

- change to the Postgres user:

`sudo su - postgres`

- create a new database user (change YOUR_USER appropriately):

`createuser -P -s -e YOUR_USER`

This will be followed by you need to input your password.

- create a new database table:

`createdb -O YOUR_USER YOUR_DB_NAME`

Change YOUR_USER and YOUR_DB_NAME appropriately.

- finally:

`psql YOUR_DB_NAME -h YOUR_HOST YOUR_USER`

This will allow you to connect to your database via your terminal.
By default, YOUR_HOST should be 0.0.0.0:5432.

You should now be able to build your database URI. This will be:

`sqldbtype://username:pw@hostname:port/db_name`

Replace sqldbtype with whichever DB you're using (eg Postgres, MySQL, SQLite, etc)
repeat for your username, password, hostname (localhost?), port (5432?), and DB name.

  ## Modules
   ### Setting load order.
   
   The module load order can be changed via the `LOAD` and `NO_LOAD` configuration settings.
These should both represent lists.

If `LOAD` is an empty list, all modules in `modules/` will be selected for loading by default.

If `NO_LOAD` is not present or is an empty list, all modules selected for loading will be loaded.

If a module is in both `LOAD` and `NO_LOAD`, the module will not be loaded - `NO_LOAD` takes priority.

   ### Creating your own modules.
   Creating a module has been simplified as much as possible - but do not hesitate to suggest further simplification.

All that is needed is that your .py file is in the modules folder.

To add commands, make sure to import the dispatcher via

`from SaitamaRobot import dispatcher`.

You can then add commands using the usual

`dispatcher.add_handler()`.

Assigning the `__help__` variable to a string describing this modules' available
commands will allow the bot to load it and add the documentation for
your module to the `/help` command. Setting the `__mod_name__` variable will also allow you to use a nicer, user-friendly name for a module.

The `__migrate__()` function is used for migrating chats - when a chat is upgraded to a supergroup, the ID changes, so 
it is necessary to migrate it in the DB.

The `__stats__()` function is for retrieving module statistics, eg number of users, number of chats. This is accessed 
through the `/stats` command, which is only available to the bot owner.

## Starting the bot.

Once you've set up your database and your configuration is complete, simply run the bat file(if on windows) or run (Linux):

`python3 -m SaitamaRobot`

You can use [nssm](https://nssm.cc/usage) to install the bot as service on windows and set it to restart on /gitpull 
Make sure to edit the start and restart bats to your needs. 
Note: the restart bat requires that User account control be disabled.

For queries or any issues regarding the bot please open an issue ticket or visit us at [Naruto Support](https://t.me/narutosupport)
## How to setup on Heroku 
For starters click on this button 
</details>  

## Credits 📍
* Well, it's all in the commit history 
Feel free to open pull requests should any be missing.
