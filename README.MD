# tg_channel_bot

# [中文详细说明 戳这！](https://github.com/ihciah/tg_channel_bot/wiki)

A telegram bot designed for syncing text/image/video from given sites to telegram channel/user/group.

自动推送指定网站的被关注用户的消息(文字、图片、视频)至 Telegram 频道、用户、群组！


You can run the program through `./tg_channel_bot -c config.json`. Check `config_example.json` for example of `config.json`.

Tips for users in China Mainland to set socks proxy:
- Linux:
```
export http_proxy=https://127.0.0.1:1080
export https_proxy=https://127.0.0.1:1080
```

- Windows:
```
set http_proxy=https://127.0.0.1:1080
set https_proxy=https://127.0.0.1:1080
```
