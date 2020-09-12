# @honka_says_bot - an animated sticker generator bot for Telegram

@honka_says_bot source
This simple script will generate text, place it onto a template sticker and send it to the chat using inline feature.

It's available at <https://t.me/honka_says_bot> and works in private and (almost) any group chats inline.

As the Bot API doesn't let you send animated stickers via inline response (yet), we have to use something more powerful, like Telethon. It has the tools we need to send animated stickers inline.

## Installation

```bash
git clone https://github.com/0x0bloodyknight/honka_says_bot.git
cd honka_says_bot
git submodule update --init --recursive
pip install -r requirements.txt
```

## Prerequisites

[api_id and api_hash](https://docs.telethon.dev/en/latest/basic/signing-in.html#signing-in)

`bot_token` can be obtained from @BotFather

## Launch

_Make sure valid `api_id`, `api_hash` and `bot_token` exist in `settings.py`_

`python bot.py`

## Thanks

Big thanks to @winsw1n and @BloodyKnight for logic, and @MattBas for his incredible lottie library ❤
