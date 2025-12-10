# Tonopah Tradier - Options Chain Viewer

A professional options chain viewer for Tradier Sandbox API.

## Features
- Real-time stock quotes
- Options chains with Greeks & IV
- ATM highlighting with gold border
- Strike interval filtering ($1/$5/$10)
- Strike range controls (±15/±30/±50)
- Resizable & draggable panels

## Requirements
- Python 3.x (for local server)
- Tradier Sandbox API token ([Get one free](https://developer.tradier.com/))

## Installation & Usage

1. Download or clone this repository
2. Navigate to the directory in terminal
3. Start a local web server:
```bash
python3 -m http.server 8080
```

4. Open your browser to: http://localhost:8080
5. Enter your Tradier Sandbox API token
6. Start trading!

## Getting a Tradier API Token

1. Visit https://developer.tradier.com/
2. Sign up for a free Sandbox account
3. Go to Account Settings → API Access
4. Copy your Sandbox API Token
5. Paste it into the app

## Version

v0.5 - Options Chain Viewer

## Privacy & Security

- Your API token is stored locally in your browser only
- No data is sent to any server except Tradier's API
- All processing happens in your browser

## License

Proprietary - All rights reserved
