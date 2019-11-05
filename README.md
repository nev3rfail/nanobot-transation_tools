# Translation Tools
[nanobot](https://github.com/nev3rfail/telegram-nanobot) plugin for Google Cloud Translate and Google Cloud TTS for Telegram

## Usage:
* Download or clone this repo
* Place JSON file with your Google Cloud credentials to nanobot-transation-tools/google-cloud-authdata.json
* Copy config.json.sample to tt.json
* Add bot token to tt.json
* Download or clone [nanobot](https://github.com/nev3rfail/telegram-nanobot) and [pyTelegramBotApi fork](https://github.com/nev3rfail/pyTelegramBotApi)
* Copy directory contents to telegram-nanobot
* run with `cd telegram-nanobot && python3 ./__init__.py --config=tt.json`
