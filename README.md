# YouTube Channel Monitoring Discord Bot

This Discord bot is designed to monitor a YouTube channel and automatically send a message to a Discord text channel upon the release of a new video.

## Setup Instructions

1. Create a new project on Glitch and import it from your GitHub repository.
2. Paste your Discord bot token into the `config.py` file.
3. Specify the Discord channel ID where the bot will send notifications.
4. Specify the YouTube channel ID to monitor.
5. Run the bot on Glitch and grant necessary intents for event handling.

## How It Works

The bot periodically checks the YouTube channel using the YouTube API and compares the ID of the latest published video with the previous state. If a new video is detected, the bot sends a notification to the specified Discord channel.

## Example Commands

- `!start`: Begin monitoring the YouTube channel.
- `!stop`: Stop monitoring.
- `!help`: Display a list of available commands.

## Contact

If you have any questions or suggestions, feel free to contact me:
- Discord: chumchik.
