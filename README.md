
<h1 align="center">FileStreamBot</h1>


``` 
💥Superfast⚡️ download and stream links.
💥No ads in generated links.
💥Superfast interface.
💥Along with the links you also get file information like name,size ,etc.
💥Updates channel Support.
💥Mongodb database support for broadcasting.
```
    
## `Star and fork the repo Before deploying`
   



## 🍁 About This Bot :

![streaming-Professional-live_1]

</p>

 ### `   This bot will give you stream links for Telegram files without the need of waiting till the download completes`





## ♢ How to make your own :


<b>Deploy on Heroku or Railway:


1. Fork This Repo <br>
2. Click on the button to Deploy and follow steps <br>
  
3.then goto the variables tab for more info on setting up environmental variables. <br>

<h4> So Follow Above Steps 👆 and then deploy other wise bot won't work</h4
  
 <p><b>Available commands and features:</b>
 
<p>
 




🐬USER COMMANDS<p>
`/start - To start using me` <br>
`/help  -  To know how to use me`

🐬ADMIN COMMANDS<p>
`/status  - to know how many users are using the bot` <br>
`/broadcast - To send message to all the users using the bot`


  
  <b>Host it on VPS Locally :</b></summary>


```py
git clone https://github.com/code-x-mania/FileStreamBot
cd FileStreamBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
python3 -m Code_X_Mania
```

and to stop the whole bot,
 do <kbd>CTRL</kbd>+<kbd>C</kbd>




Setting up things

If you're on Heroku / Railway, just add these in the Environmental Variables
or if you're Locally hosting, create a file named `.env` in the root directory and add all the variables there.
An example of `.env` file:

```py
DATABASE_URL=  Get this from mongodb.com
PORT=8080
API_ID= Get from my.telegram.org
NO_PORT=False
BOT_TOKEN= Get from botfather
OWNER_ID= your owner id 
API_HASH= Get from my.telegram.org
UPDATES_CHANNEL= Enter Force sub channel username without @ if any  else set value to None
BIN_CHANNEL=-100
SESSION_NAME=Codexmania
HAS_SSL=True
FQDN= Enter Custom domain if any or server ip
```
 





<b>Vars and Details :</b>

`API_ID` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.

`APP_NAME` : Your Heroku App Name.

`API_HASH` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.

`BOT_TOKEN` : Get the bot token from [@BotFather](https://telegram.dog/BotFather)

`BIN_CHANNEL` : Create a new channel (private/public), add [@missrose_bot](https://telegram.dog/MissRose_bot) as admin to the channel and type /id. Now copy paste the ID into this field.

`OWNER_ID` : Your Telegram User ID
  
`OWNER_USERNAME` : Your telegram username to be displayed in bot  . make one in you dont have.

`DATABASE_URL` : MongoDB URI for saving User IDs when they first Start the Bot. We will use that for Broadcasting to them. I will try to add more features related with Database. If you need help to get the URI you can ask in [Telegram](https://t.me/codexmania).

 Optional Vars

`UPDATES_CHANNEL` : Put a Public Channel Username, so every user have to Join that channel to use the bot. Must add bot to channel as Admin to work properly.

`BANNED_CHANNELS` : Put IDs of Banned Channels where bot will not work. You can add multiple IDs & separate with <kbd>Space</kbd>.

`SLEEP_THRESHOLD` : Set a sleep threshold for flood wait exceptions happening globally in this telegram bot instance, below which any request that raises a flood wait will be automatically invoked again after sleeping for the required amount of time. Flood wait exceptions requiring higher waiting times will be raised. Defaults to 60 seconds.

`WORKERS` : Number of maximum concurrent workers for handling incoming updates. Defaults to `3`

`PORT` : The port that you want your webapp to be listened to. Defaults to `8080`

`WEB_SERVER_BIND_ADDRESS` : Your server bind adress. Defauls to `0.0.0.0`

`NO_PORT` : If you don't want your port to be displayed. You should point your `PORT` to `80` (http) or `443` (https) for the links to work. Ignore this if you're on Heroku.

`FQDN` :  A Fully Qualified Domain Name if present. Defaults to `WEB_SERVER_BIND_ADDRESS` </details>

<b>How to Use :</b>



:warning: **Before using the  bot, don't forget to add the bot to the `BIN_CHANNEL` as an Admin**
 


`/start` : To check if the bot is alive or not.



To get an instant stream link, just forward any media to the bot and boom, its fast af.
![image]


