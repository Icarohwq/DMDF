![wp9371426](https://user-images.githubusercontent.com/126829731/222923171-182cfdfa-e402-4255-ba27-91415a287c99.jpg)


> For educational purposes only

# TEMPORARILY FREE
- any questions can ask
- leave your feedback!! 

# Download
- [Click here to download](https://we.tl/t-OmlfQ615kL)

## Threads

- The threads are per server
- 10 threads = 10 tokens per server
- No use multi-thread for join

- I recommend 10, if you are using tokens from different dates you can use more without problems, a maximum of 10 tokens from the same day 
- Server Flag = A much lower DM average


## Captcha Service

- Services with official suporte 
- https://api.anti-captcha.com (recommended for join)
- https://api.capsolver.com (recommended for dm)
- https://api.capmonster.cloud (not recommended)


## MongoDB

- https://account.mongodb.com/account/login (online db)
- https://www.mongodb.com/try/download/community (download local host)

- [mongodb://localhost:27017] for localhost (Recommended)
- [mongodb+srv://user:password@cluster0.pyabp0c.mongodb.net/test] for online


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
#Oficial suporte api.anti-captcha.com, api.capsolver.com, api.capmonster.cloud  

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

![Captura de tela de 2023-03-05 04-03-13](https://user-images.githubusercontent.com/126829731/222946697-cbab89d2-7dad-4491-a726-e03e44af23d6.png)

## Terms

-  Do not pass on your license to third parties
-  Do not send the program to third parties
-  Do not act in bad faith
-  Breach of terms can and will cause you to lose your license\

`By` `Icaro.A [AToS]#7514` Discord Society
