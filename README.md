# Simple Discord Bot with Discord.py

### Features:

- Imports necessary modules: os, discord, commands (from discord.ext), and load_dotenv from the dotenv library.
- Configures intents using the default_intents object to track server member joins.
- Initializes the bot with commands.Bot, setting the command prefix as "!" and configuring intents.
- Triggers the on_ready event, displaying a message in the console when the bot is ready.
- Handles the on_member_join event, logging the name of new members in the console.
- Defines a command !del using @bot.command(name="del"), which takes a 'number' argument to delete a specified number of messages in the command's channel.
- Runs the bot using bot.run(os.getenv("TOKEN")), retrieving the Discord bot token from environment variables.

### Usage:

- Monitor on_ready and on_member_join events.
- Utilize the !del command to delete messages in a channel.

---

PS : Please remember to activate the virtual environment.

