# TM_MyTelegramORG

~~(yet)~~ another my.telegram.org scrapper inside Telegram.

- can be found on [Telegram](https://telegram.dog/TM_MytelegramOrgBot)

## installing

## Deploy 

<b>Deploy on Heroku</b>
<p align="left">
  <a href="https://heroku.com/deploy?template=https://github.com/TechyMask/TM_MyTelegramOrg">
     <img height="30px" src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku">
  </a>
</p>

##Deploy in your VPS
- clone the repository, locally.
```sh
git clone https://gitHub.com/TechyMask/TM_MyTelegramOrg.git
```

- change the directory.
```sh
cd TM_MyTelegramOrg
```

- create a virtual environment.
```sh
virtualenv -p /usr/bin/python3 venv
```

- activate the virtual environment.
```sh
. ./venv/bin/activate
```

- install the requirements.
```sh
pip install -r requirements.txt
```

- create config.py

- run the bot
```sh
python3 bot.py
```

## [@TechyBots](https://t.me/TechyBots/)

- Only `TG_BOT_TOKEN` environment variables is mandatory.
- The Telegram RoBot should work without setting the non-mandatory variables.
- Please report any issues to the support Admin: [@Admin](https://t.me/WhoisYumikoBot)


## learning

check out the [helper_funcs](helper_funcs) directory, to see how my.telegram.org is scrapped.

## LICENSE
[AGPLv3]((LICENSE)

## credits

- Libraries Used:
  - [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
  - [requests](https://github.com/psf/requests)
  - [beautifulsoup4](https://pypi.org/project/beautifulsoup4)
