# YouTube to MP3 Telegram Bot

A Telegram bot that downloads YouTube videos and converts them to MP3 audio files.

## Prerequisites

- Python 3.10+
- ffmpeg (system dependency)

### Install ffmpeg

**Ubuntu/Debian:**
```bash
sudo apt update && sudo apt install ffmpeg
```

**macOS:**
```bash
brew install ffmpeg
```

**Windows:**
Download from [ffmpeg.org](https://ffmpeg.org/download.html)

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Your bot token is already configured in `.env` file

## Run

```bash
python bot.py
```

## Usage

1. Start a chat with your bot on Telegram
2. Send `/start` to see the welcome message
3. Send any YouTube URL
4. Wait for the bot to download, convert, and send the MP3 file

**develop by** : github.com/demiee-01
