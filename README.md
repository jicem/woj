# Woj Bot
Woj Bot is a fork of the bbgmBot Discord bot that reads and displays data from export files from the game http://www.basketball-gm.com/. It can do these things, among many more features:
• Show player ratings, stats, and bio information.
• Show team rosters with stats and contracts.
• Show draft picks and projected records for teams.
• Show award, progression, and recent game history for players.

More features are being added on a somewhat regular basis, with the goal of helping out Basketball GM multiplayer servers in making information easily accessable to people who can't access export files (for example, if out and on mobile). 

INSTALLATION
1. If not already done, install discord.py.
2. You need to set up the bot part yourself. There are online tutorials, but you'll want to start with the Discord Developer Portal. Once you have a bot set up, you need the token from it.
3. Open main.py and add the bot token to the bottom where it says "your_token". Keep the quotes around it. 
4. Run the file - you should notice your bot come online.


USAGE
1. To load an export file, run "-load" and then follow it with a direct link to a JSON file. Nothing will work until a file is loaded for the server it's in. Only people with "Manage Roles" permission can load exports.
2. Run -help to see all commands, enjoy.

BUGS
1. I'm aware that there are probably various issues, particularly when dealing with newer leagues that haven't been simmed very many seasons. If you can send an export file to me as well as which command(s) isn't/aren't working, I'll look into it.

Made by ClevelandFan295 and updated by Jicem
