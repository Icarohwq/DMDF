![DMDF](https://user-images.githubusercontent.com/127346906/224520680-ae2c6ff6-c244-4f48-bc14-98df87d075ca.jpg)


> For educational purposes only


# Buy / Download
- **Buy** Licesence [here](https://discordsociety.sellix.io/product/640d2ced7cd1e) (after purchase put your license in "license")
- [Click here to download DMDF [v1.6.2]](https://we.tl/t-q8DgpH89T3)


## Threads

- The threads are per server
- 10 threads = 10 tokens per server
- No use multi-thread for join

- I recommend 10, if you are using tokens from different dates you can use more without problems, a maximum of 10 tokens from the same day 
- Server Flag = A much lower DM average


## **Captcha solver**
- Qill only be released in the **paid version**
- **don't pay captcha to send messages**


## Captcha Services

- Services with official suporte 
- https://api.anti-captcha.com
- https://api.capsolver.com
- https://api.capmonster.cloud 


## MongoDB

- https://account.mongodb.com/account/login (online db)
- https://www.mongodb.com/try/download/community (download local host)

- `mongodb://localhost:27017` for localhost (Recommended)
- `mongodb+srv://user:password@cluster0.pyabp0c.mongodb.net/test` for online


## Operating Mode

-  Start x Threds per server
-  Join tokens in server 
-  Start mass dm
-  Repeats the process for all servers under [Data/Servers]


## Config

- `KeyCaptcha` The captcha service key (Leave empty to disable)
-  `DomainCaptcha` Url of the captcha service api located in 
- `Proxy` type://user:pass@ip:port or type://user:pass:ip:port
-  `DelayOnStart` Delay for binding tokens (per server)
-  `DelayOnMessage` Sleep every 1 message (I recommend 85)
-  `SleepRatelimit` Sleeps every 10 messages x seconds
-  `SleepAfterXDM` execute DelayOnRatelimit after try send x dm

##### EXAMPLE

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

#Oficial suporte dmdfsolver.atos (FOR IA SOLVER [FREE]), api.anti-captcha.com, api.capsolver.com, api.capmonster.cloud  

KeyCaptchaForDM = "CAI-xxxx"  
DomainCaptchaForDM = "api.capsolver.com"  
  
KeyCaptchaForJoin = "xxxxx"  
DomainCaptchaForJoin = "api.anti-captcha.com"
```

## Message features

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

![DMDF-MAIN](https://media.discordapp.net/attachments/1050232164383461446/1084076506193596457/image.png?width=843&height=474)

## Contact
- https://t.me/ATOS_DMDF
- `Icaro.A [AToS]#7514`

## Terms

-  Do not pass on your license to third parties
-  Do not send the program to third parties
-  Do not act in bad faith
-  Breach of terms can and will cause you to lose your license
