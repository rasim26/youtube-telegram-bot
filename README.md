# YouTube to Telegram Bot

A Python bot that connects a YouTube channel to Telegram.  
It lists recent videos and playlists on command, and automatically notifies a Telegram chat or channel when new videos are uploaded.

## Features

- `/videos` — Get the latest videos from your YouTube channel.
- `/playlists` — List all playlists from your YouTube channel.
- **Automatic notifications** — The bot checks for new uploads and sends a message to your Telegram chat or channel.

## Requirements

- Python 3.7+
- [python-telegram-bot](https://python-telegram-bot.org/)
- [google-api-python-client](https://github.com/googleapis/google-api-python-client)
