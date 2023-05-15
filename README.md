# DMDF Bot
![DMDF](https://user-images.githubusercontent.com/127346906/224520680-ae2c6ff6-c244-4f48-bc14-98df87d075ca.jpg)

DMDF Bot is an advanced Discord message automation tool, developed for educational purposes. Our bot allows you to send bulk messages, optimize response time, and even solve captchas in an automated way. This is especially beneficial for users who need an effective solution for managing multiple servers.

> **Note:** This software is made available for educational purposes only.

## Features

1. **Threads per server**: Configure the number of threads per server, optimizing token distribution.
2. **Captcha Solver**: Our bot is equipped with artificial intelligence capable of solving captchas, saving you time and money.
3. **Support for multiple Captcha services**: DMDF officially supports api.anti-captcha.com, api.capsolver.com, and api.capmonster.cloud.
4. **MongoDB Support**: DMDF Bot supports MongoDB for efficient data management.

## Purchase / Download
- **Purchase License:** [License Link](https://discordsociety.sellix.io/product/640d2ced7cd1e)
- **Download:** [Download Link](https://t.me/ATOS_DMDF)

## How DMDF Bot Works

DMDF Bot operates using a multi-thread system. Each Discord server gets its own set of threads. Each thread is responsible for managing a single 'token', which is a key that allows the bot to interact with the server. Threads are distributed as per the number set by the user.

For instance, if the user sets that they want to use 10 threads and they have 10 servers, the bot will initiate 10 tokens on each server. This means that, in total, the bot will be managing 100 tokens simultaneously (10 on each of the 10 servers).

This system is designed to avoid detection by anti-bot systems. Many Discord servers have detection mechanisms in place to identify when multiple tokens (especially tokens created at the same time) are interacting with the server simultaneously. By distributing the tokens across multiple threads and ensuring that the tokens initiated at each server are of different ages, DMDF Bot can effectively bypass this detection.

Furthermore, DMDF Bot has an integrated AI-based captcha solver, which distinguishes it from other bots. This AI solver can automatically solve captchas, saving users from the cost of manual captcha-solving services.

In terms of operation, DMDF Bot follows these steps:

1. Starts 'x' number of threads per server as defined by the user.
2. Joins tokens in the server.
3. Starts mass messaging.
4. Repeats the process for all servers listed under the [Data/Servers] directory.

This process ensures efficient and seamless operation while minimizing the risk of detection by anti-bot systems.


## Configuration

To configure the DMDF Bot, you will need to adjust the following parameters in the 'config.toml' file:

```toml
JoinTokens = true
TryBypassCaptcha = false  

Threads = 10    
DelayOnStart = 75  
SleepAfterXDM = 9  
DelayOnMessage = 70  
DelayOnRatelimit = 600  
MaxDMOpensPerToken = 600  

MongoURL = "mongodb+srv://user:pass@cluster0.pyabp0c.mongodb.net/test"  

#Oficial support dmdfsolver.atos (IA SOLVER [FREE]), api.anti-captcha.com, api.capsolver.com, api.capmonster.cloud  

KeyCaptchaForDM = "CAI-xxxx"  
DomainCaptchaForDM = "api.capsolver.com"  
  
KeyCaptchaForJoin = "xxxxx"  
DomainCaptchaForJoin = "api.anti-captcha.com"
```


## Tutorial

For a detailed tutorial on how to configure and use the DMDF Bot, visit our [tutorial](https://t.me/ATOS_DMDF/5).

## Contact

For support and more information, you can contact us through the following channels:

- Telegram: [ATOS_DMDF](https://t.me/ATOS_DMDF)
- Discord: `icaro#0001`

## Terms of Use

By acquiring the DMDF Bot license, you agree to the following terms:

1. Do not pass on your license to third parties.
2. Do not distribute the program to third parties.
3. Do not use the program in bad faith.
4. Violation of these terms can and will result in the loss of your license.

Failure to comply with these terms may result in the termination of your license without notice or refund.

## Message Features

In your messages, you can use the following features:

- `{user}` mention user 
- `{username}` username
- `{channel}` mention user channel
- `{time}` current time 
- `{timed}` time the message was sent

## Tutorial

1. Configure data/config.toml
2. Put targets (users ids) in data/Servers/{ServerInvite}.txt
3. Put tokens in data/tokens.txt
4. Start Tool
5. [VIDEO TUTORIAL](https://t.me/ATOS_DMDF/5)

![DMDF-MAIN](https://media.discordapp.net/attachments/1083986985196191758/1104237114700341328/photo_2023-05-05_15-51-03.jpg?width=1193&height=555)

## Contact
- https://t.me/ATOS_DMDF
- `icaro#0001`

## Terms

-  Do not pass on your license to third parties
-  Do not send the program to third parties
-  Do not act in bad faith
-  Breach of terms can and will cause you to lose your license
