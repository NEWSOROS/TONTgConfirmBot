# TONTgConfirmBot

This is telegram bot for transaction confirmation.

## Installation in 4 simple steps (1 minute, and your bot is ready)

 1. Create your personal telegram bot and get Api Token. [Instruction](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-4.0)
 2. Send to your new bot command /start and go to the next step
 3. Run command below
```sh
$ cd $HOME && git clone -v https://github.com/NEWSOROS/TONTgConfirmBot.git tontgconfirmbot && cd ./tontgconfirmbot && chmod +x ./install.sh
```
 4. Run 
 ```sh
$ /bin/bash ./install.sh
```
## Update

 1. Run command below
```sh
$ cd $HOME && cd ./tontgconfirmbot && git pull && chmod +x ./install.sh && ./install.sh
```

## Confirmation

When bot send you information about new transaction, just reply to him with simple command /confirm ID

Example:

/confirm 0x5f19e9eceb3585c1
