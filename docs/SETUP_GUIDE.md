# TG Story Watcher - Setup Guide

## Prerequisites
- Python 3.10+
- Telegram API credentials (api_id, api_hash)

## Get Telegram API Credentials
1. Go to https://my.telegram.org
2. Log in with your phone number
3. Click "API Development Tools"
4. Create a new application
5. Save your api_id and api_hash

## Installation
```bash
git clone https://github.com/devlewicki/TG-Story-Watcher.git
cd TG-Story-Watcher
pip install -r requirements.txt
cp .env.example .env
python main.py
```

## Features
| Feature | Description |
|---------|------------|
| Auto-view | Automatically views stories |
| Web UI | Monitor from browser |
| Self-hosted | Your data stays private |
| Notifications | Get alerts for new stories |