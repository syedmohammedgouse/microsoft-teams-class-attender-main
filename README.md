
# microsoft-teams-class-attender-main
REQUIREMENTS 

certifi==2020.6.20
chardet==3.0.4
Discord-Webhooks==1.0.4
idna==2.8
requests==2.21.0
schedule==0.6.0
selenium==3.141.0
urllib3==1.24.3



This bot attends the online classes (or meetings) held on Microsoft teams, according to the given timetable.

Configure

There are few things you need to configure before running this bot.

Open Microsoft teams on your browser, login to your account, change the dashboard view to list view (from grid view), so that your classes are displayed in a list view.


This is how list view looks like




Open bot.py, and put your microsoft teams credentials in the CREDS dictionary.


Example - CREDS = {'email' : 'myemail@email.com', 'passwd':'''mypassword'''}


Open discord_webhook.py and put your discord webhook URL in the webhook_url variable.


Example - webhook_url = "https://discordapp.com/...."


Make sure that the timezone of the PC is correct. If you're running the bot on cloud, you may want to manually change the timezone of the virtual machine to an appropriate time zone (i.e., the timezone that your online classes follow)



Install


Run the bot

Run the bot python bot.py

Written on Python3.
