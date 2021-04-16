
## GoodVibesUserBot ❤️️

|Deploy To Heroku|  
|--|
| [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template= https://github.com/GoodVibes-1/GoodVibeesUserBot) | [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)] |

### Setting Up Locally 👇🏻

 - Fill in the required fields in **"sample_config.py"**
 - Install the required libraries with **requirements.txt**.
( `pip3 install -r requirements.txt` )

 - And then start the bot. ( `python3 -m userbot` )
 - If you did it correctly, the bot will run successfully.


### Create String Session

[![Run on Repl.it](https://repl.it/badge/github/jasonalantolbert/replit-badger)](https://repl.it/@furki/telegram-session)

### Example Plugin

  ```python
  from  datetime  import  datetime
from userbot import bot
from userbot.util import admin_cmd

@bot.on(admin_cmd(pattern="ping"))
async def ping(event):
	start  =  datetime.now()
	await  event.edit("Pong!")
	end  =  datetime.now()
	ms  = (end  -  start).microseconds  /  1000
	await  event.edit("Pong!\n`{}`".format(ms))
```

### İletişim ✍️

Herhangi bir sorunla karşılaşırsanız, bana bildirmekten çekinmeyin. Bu bağlantıyı kullanarak benimle iletişime geçebilirsiniz  [Poyraz](https://t.me/Poyraz2103).

### License ⚠️
-   Copyright (C) 2020 by  [POYRAZ](https://github.com/matesa)  ❤️️
-   Licensed under the terms of the  [Mozilla Public License 2.0](https://github.com/GoodVibes-1/GoodVibeesUserBot/blob/master/LICENSE)
