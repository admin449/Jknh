SN-WZML-Modified By Kartik Lakhotiya

This repo is the edited version of https://github.com/SN-Abdullah-Al-Noman/SN_WZML 
So all credit goes to the respective owner 

I have just edited some fonts so that your mirror bot can look cool.

Deployment Method :-
1. Fork / Template my repo.

2. Rename config_sample.env to config.env and then add the vars u need in config.env.

3. Upload token.pickle / accounts directory / credentials.json in heroku branch (token and credentials is must without these uploading to gdrive won't work)

4. Go to repo settings tab scroll download click on secrets and variable under the security head then click on actions add the following repository secrets.       
   `HEROKU_EMAIL` - Your heroku email ID .       
   `HEROKU_APP_NAME` - Your heroku appname make sure it is unique and must be same as the BASE_URL_OF_BOT in config.env        
   `HEROKU_API_KEY` - Your heroku api key which u can get from your heroku account settings.
   
5. Go to Actions tab and then run the workflow (heroku one).

6. If you see Info - Bot Sarted !!! Message in your heroku logs it means bot successfully deployed.


Don't set EMOJI_THEME var to true. My edits won't work then.


NOTE - I am just changing some string values which won't give any errors during the working of the mirror bot. So, if u face any error regarding this please contact the support group of the original repo or you can contact me via Telegram (id is below).

WARNING !!!!       
Don't use /qbmirror command to mirror torrent just use normal /mirror command if you use qbmirror you heroku account will get banned.

Credits :-

https://t.me/AtrociousBotSupport     
https://t.me/ItsBitDefender      
https://t.me/MrKartikL
