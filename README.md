# 🗿 TalkyTrader

<img src="https://i.imgur.com/Q7iDDyB.jpg" align="right"
     alt="talky" width="400" height="400">



## Features


<br>

<!-- <img src="https://raw.githubusercontent.com/onwidget/.github/main/resources/astrowind/screenshot-astro2.jpg" alt="AstroWind Theme Screenshot"> -->

ℹ️ Information is available on the different talky modules

🐛 If you find an issue you'd like to report, or otherwise have feedback, please add a new Issue <a href="https://github.com/mraniki/tt/issues"><img src="https://badgen.net/github/open-issues/mraniki/tt" /></a>

🧑‍💻 If you'd like to contribute, please start by creating or commenting on an <a href="https://github.com/mraniki/tt/issues">issue</a> so we can track the work. 

💬 Share your feedback and connect on <a href="https://discord.gg/vegJQGrRRa"><img src="https://badgen.net/badge/icon/discord/purple?icon=discord&label" /></a> <a href="https://t.me/TTTalkyTraderChat/1"><img src="https://badgen.net/badge/icon/telegram?icon=telegram&label" /></a>

🍩 If you like it, feel free to <a href="https://coindrop.to/mraniki"><img src="https://badgen.net/badge/icon/coindrop/6F4E37?icon=buymeacoffee&label"/></a>

⚠️ This is an education tool and should not be considered professional financial investment system nor financial advice. Use a testnet account or USE AT YOUR OWN RISK. For DEX, Never share your private keys. NEVER use your main account for automatic trade

<br>

<details close>
<summary>Get started</summary>

1) Create your channel/room and your platform bot

    - Telegram via [Telegram @BotFather](https://core.telegram.org/bots/tutorial) and [create an API key](https://docs.telethon.dev/en/stable/basic/signing-in.html) 
    - Discord via [Discord Dev portal](https://discord.com/developers/docs/intro)
    - Matrix via [Matrix.org](https://turt2live.github.io/matrix-bot-sdk/index.html)

2) Get your

    - CEX API Keys supported by [CCXT](https://github.com/ccxt/ccxt) or
    - DEX wallet address and private key

3) Create your config [/app/settings.toml](src/example_settings.toml) or prepare your env variable

4) Deploy via:
    - docker `docker pull mraniki/tt:latest` or `docker pull ghcr.io/mraniki/tt:latest`
    - locally `git clone https://github.com/mraniki/tt:main` && `pip install -r requirements.txt`

5) Start your container or if deployed locally use `python3 bot.py` to start

6) Documentation available on [Wiki](https://talkytrader.github.io/wiki/)Start your container or if deployed locally use `python3 bot.py` to start

</details>


<br>

## Commands

- /bal Query user account exchange balance
- /trading Disable or Enable trading
- /q wBTC retrieve the lastest asset quote
- `sell BTCUSDT sl=6000 tp=4500 q=1%`, sell BTCUSDT or any order matched by FindMyOrder module. Default order identifier are buy, sell, long and short but can be modified as a setting.
<br>

## Configuration


https://github.com/mraniki/tt/blob/dc394d42d18e3718e0062f32cdfccb006b9c716a/examples/example.env#L2



<script src="https://emgithub.com/embed-v2.js?target=https%3A%2F%2Fgithub.com%2Fmraniki%2Ftt%2Fblob%2Fmain%2Fexamples%2Fexample.env&style=default&type=markdown&showLineNumbers=on&showCopy=on&fetchFromJsDelivr=on"> </script>


<br>

## Deploy

<br>

## Module
### Talky
  
Submit trading order to CEX & DEX with multi messaging platform and plugin support

### FindMyOrder

Find that order

### DXSP

Swap made easy

### IamListening

Build a chat listener bot

### TalkyTrend

Get the trend

<br>

## Demo

<!-- 📌 [https://talky.vercel.app/](https://talky.vercel.app/) -->

<img width="194" alt="222953459-0aaf024b-4d7b-4a57-b31b-7cab08f3c0d3" src="https://github.com/mraniki/tt/assets/8766259/14cb1653-f6b4-44e7-b07c-d930060c7363">

<br>


## Frequently Asked Questions



## Contributing



## Acknowledgements

