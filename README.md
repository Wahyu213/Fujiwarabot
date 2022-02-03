<h2 align="center">
    ──「𝐂𝐡𝐢𝐤𝐚 𝐅𝐮𝐣𝐢𝐰𝐚𝐫𝐚」──
</h2>

<p align="center">
  <img src="https://telegra.ph/file/193b10ac0eefdc9316a8e.jpg">
</p>

<h3 align="center">
    Telegram Group Manager Bot Written In Python Using Pyrogram.


# Chika Robot 
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![GPLv3 license](https://img.shields.io/badge/License-MIT-blue.svg)](https://perso.crans.org/besson/LICENSE.html) [![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com) [![Updates channel!](https://img.shields.io/badge/Join%20Channel-Zoning-red)](https://t.me/nbzoning) [![Join Support!](https://img.shields.io/badge/Support%20Chat-Chika-red)](https://t.me/OkaeriUserbot)


A modular Telegram Python bot running on python3 with a sqlalchemy database and an entirely themed persona to make Chika suitable for Anime and Manga group chats. 

The Support group can be reached out to at [Chika Support](https://t.me/OkaeriUserbot), where you can ask for help about discover/request new features, report bugs, and stay in the loop whenever a new update is available. 

News channel as at [Chika Updates](https://t.me/nbzoning) 


## Stats
![Wahyu's Github stats](https://github-readme-stats.vercel.app/api?username=Wahyu213&show_icons=true&theme=tokyonight)

 ## Credits
 - [TheHamkerCat](https://github.com/TheHamkerCat)

## How to setup/deploy.

### Read these notes carefully before proceeding 
 - Edit any mentions of @OkaeriUserbot to your own support chat. 
 - Lastly, if you are found to run this repo without the code being open sourced or the repository link not mentioned in the bot, we will push a gban for you in our network because of being in violation of the license, you are free to be a dick and not respect the open source code (we do not mind) but we will not be having you around our chats.


<details>
  <summary>Steps to deploy on Heroku !! </summary>

```
Fill in all the details, Deploy!
Now go to https://dashboard.heroku.com/apps/(app-name)/resources ( Replace (app-name) with your app name )
REMEMBER: Turn on worker dyno (Don't worry It's free :D) & Webhook
Now send the bot /start, If it doesn't respond go to https://dashboard.heroku.com/apps/(app-name)/settings and remove webhook and port.
```
 Deploy

  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Wahyu213/Fujiwarabot.git)

</details>  
<details>
  <summary>Steps to self Host!! </summary>

  ## Setting up the bot (Read this before trying to use!):
Please make sure to use python3.6, as I cannot guarantee everything will work as expected on older Python versions!
This is because markdown parsing is done by iterating through a dict, which is ordered by default in 3.6.

  ### Configuration

There are two possible ways of configuring your bot: a config.py file, or ENV variables.

The preferred version is to use a `config.py` file, as it makes it easier to see all your settings grouped together.
This file should be placed in your `ChikaRobot` folder, alongside the `__main__.py` file. 
This is where your bot token will be loaded from, as well as your database URI (if you're using a database), and most of 
your other settings.

It is recommended to import sample_config and extend the Config class, as this will ensure your config contains all 
defaults set in the sample_config, hence making it easier to upgrade.

  ### Python dependencies

 ```
- Install the necessary Python dependencies by moving to the project directory and running:
- `pip3 install -r requirements.txt`.
- This will install all the necessary python packages.
```
