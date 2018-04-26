# discord-bots
A repo for Caius' Discord Bots

These bots require a file `secrets.txt` to reside in the same directory, which contains Caius' discord app tokens, so don't try nothin funny. 

discord.py API documentation: http://discordpy.readthedocs.io/en/latest/api.html

To add a bot to a channel: https://discordapp.com/oauth2/authorize?&client_id=YOUR_CLIENT_ID_HERE&scope=bot&permissions=0

## To Do
* Create a Mother bot
  * Update/restart bots via discord DMs
  * DM Caius on unexpected shutdown
* Bot command inheritance
* More robust generic command handling (i.e. doing things that aren't send_message) 
  * allow callables to be returned by commands somehow? problems with async
* Logging
* Daemon/Cronjob
