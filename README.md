# REMChain-Automated-Bot

REMChain-Automated-Bot is a fully customisable script which monitors and manages your Guardians and Producer node. It also allows Guardians and Producers the flexibility to choose whether to have their votes, claims and even a percentage of their claimed rewards restaked or transfered out automatically every 24 hours. Furthermore it also has a built in monitor which monitors and alerts you whenever your node faces issues within the set intervals.

<br>

***

<br>

## Step 1: Create Telegram Bot Using Botfather

<br>

#### The following steps describe how to create a new bot:

* Contact [**@BotFather**](https://telegram.me/BotFather) in your Telegram messenger.
* To get a token, send BotFather a message that says **`/newbot`**.
* When asked for a name for your new bot choose something that ends with the word bot, so for example my_test_bot.
* If your chosen name is available, BotFather will then send you a token.
* Save this token as you will be asked for it once you execute the script.

Once your bot is created, you can set a custom name, profile photo and description for it. The description is basically a message that explains what the bot can do.

#### To set the Bot name in BotFather do the following:

* Send **`/setname`** to BotFather.
* Select the bot which you want to change.
* Send the new name to BotFather.

#### To set a Profile photo for your bot in BotFather do the following:

* Send **`/setuserpic`** to BotFather.
* Select the bot that you want the profile photo changed on.
* Send the photo to BotFather.

#### To set Description for your bot in BotFather do the following:

* Send **`/setdescription`** to BotFather.
* Select the bot for which you are writing a description.
* Change the description and send it to BotFather.

There are some other useful methods in BotFather which we won't cover in this tutorial like **`/setcommands`**.
<br>

***

## Step 2: Obtain Your Chat Idenification Number
<br>
Theres two ways to retrieve your Chat ID, the first is by opening the following URL in your web-browser: 

[**https://api.telegram.org/botTOKEN/getUpdates**](https://api.telegram.org/botTOKEN/getUpdates) then replace the **`TOKEN`** with your actual bot token.

Your Chat ID will be shown in this format **`"id":7041782343`**, based on this example your Chat ID would of been **`7041782343`**. The second way that this can be done is through a third party telegram bot called [**@get_id_bot**](https://telegram.me/get_id_bot).
<br>

***

## Step 3: Download The Scripts Required For Monitoring and Managing Your Guardian Or Producer.

<br>

## `AUTOBOT: AUTOMATING VOTES, CLAIMING, RESTAKING & TRANSFERS`

<br>

#### Setup 1: Download REMChain And Import Guardian Key

<br>

```
sudo wget https://github.com/remblock/REMChain-Automated-Bot/raw/master/autobot-setup1 && sudo chmod u+x autobot-setup1 && sudo ./autobot-setup1 --at
```
<br>
  
#### Setup 2: Download And Install Autobot

<br>

```
sudo wget https://github.com/remblock/REMChain-Automated-Bot/raw/master/Guardian-Autobot-Setup2 && sudo chmod u+x Guardian-Autobot-Setup2 && sudo ./Guardian-Autobot-Setup2 --at
```

<br>

#### Please Note: You will need to change the default key permissions:

```
nano remblock/autobot/config file
```
