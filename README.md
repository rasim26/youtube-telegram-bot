# YouTube to Telegram Bot

A Python bot that connects a YouTube channel to Telegram.  
It lists recent videos and playlists on command, and automatically notifies a Telegram chat or channel when new videos are uploaded.

## Features

- `/videos` — Get the latest videos from your YouTube channel.
- `/playlists` — List all playlists from your YouTube channel.
- **Automatic notifications** — The bot checks for new uploads and sends a message to your Telegram chat or channel.

## Example 
Here’s how the bot responds to the `/videos` command:

- <img width="1141" height="854" alt="Screenshot 2025-07-24 at 5 53 58 PM" src="https://github.com/user-attachments/assets/cb13caad-9f81-4b1e-88c8-7a1d401058fb" />


## Requirements

- Python 3.7+
- [python-telegram-bot](https://python-telegram-bot.org/)
- [google-api-python-client](https://github.com/googleapis/google-api-python-client)
