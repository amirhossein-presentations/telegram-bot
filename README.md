<p align="center">
  <img src="https://miro.medium.com/max/1400/1*JUF8QTMUpJiKXMcM8EvvaQ.jpeg" width="300" alt="logo" />
</p>

<h1 align="center">
Go Telegram Bot
</h1>

This is a **Telegram** bot to get the latest NBA results. The idea behind this project is to
work with telegram apis in golang.

## How to run ths project?
To run the bot, first you need to create a bot in **Telegram**, then
save your _bot api token_ somewhere.

Now clone the project:
```shell
git clone https://github.com/amirhnajafiz/nba-bot.git
```

Now copy the configs:
```shell
cp ./configs/configs.yaml ./config.yaml
```

After that place your token in the config file:
```yaml
telegram:
  token: "[BOT API TOKEN]"
```

Now you can run the application by the following command:
```shell
make build
make run
```

You should see the following response:
```
Waiting for telegram bot to start ...
Bot started.
```

## Routes
Now you can test the bot in telegram by the following command:
- /test

And for getting NBA results, use the following commad:
- /view
