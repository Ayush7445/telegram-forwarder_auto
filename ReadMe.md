# Channel Auto-Post Bot

This makes a user send all messages from one/many chat(s) to another chat(s).

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

[![YouTube Video](https://img.shields.io/badge/youtube-video-red)](https://youtu.be/_83nexTIUaU) - Deploy Tutorial On YouTube

## Setting up 
* First:
> `APP_ID` and `API_HASH` - Get it from my.telegram.org   
> `SESSION` - A telethon session string, get it from [here](https://replit.com/@TeamUltroid/UltroidStringSession).   
> `FROM_CHANNEL` - Channel ID(s) split by space or just one channel ID.   
> `TO_CHANNEL` - Channel ID(s) split by space or just one channel ID.   

* Chose a platform to deploy on:
<details>
<summary>Heroku/Kintohub/Zeet</summary>
<br>
Add the above values to the environment vars and deploy the bot.
</details>
<details>
<summary>Local Deoploys</summary>
<br>
- Clone the repo:   <code>git clone https://github.com/Ayush7445/telegram-auto_forwarder</code></br>
- Make a <code>.env</code> file in the root of the repo, like <a href="https://github.com/Ayush7445/telegram-auto_forwarder/blob/main/.env.sample">.env.sample</a> and fill in the values.</br>
- Use <code>python3 bot.py</code> to start the bot.</br>  
</details>

## Usage
All new messages will be auto-posted!!
Join the channel from you want the posts to be taken.
Join as admin in the channel where you want the posts to be sent to.

[![Telegram Channel](https://img.shields.io/badge/Telegram-Channel-blue)](https://t.me/joinchat/QiGxI8jGZKA4Mjll) - Join it for Update purpose. 

## Credits
> [Lonami](https://github.com/LonamiWebs), for [Telethon](https://github.com/LonamiWebs/Telethon).   
