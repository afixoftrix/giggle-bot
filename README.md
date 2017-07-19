# Giggle Bot
What is giggle bot?
Giggle bot is a slack bot that increases the humor levels of your slack chat room. It does this by reading trigger words from the slack channel through the slack api and returning a joke or a meme-ish picture (depending on the input).

## Automatic Deployment
This app has the ability to be deployed directly from Heroku.

First, you will need a slack token from slack.
To get this you must be part of a slack channel. You can create your own if you prefer.
Next visit: https://my.slack.com/services/new/bot to create a new bot.
You can name the bot whatever you want your giggle-bot to be called. Then  click `Add bot integration`.
Copy the displayed token.
![Image](/assets/apitoken.png)
This token will be used on Heroku for deployment and will be required when you click the deploy link below:

[![Deploy](https://www.Herokucdn.com/deploy/button.svg)](https://Heroku.com/deploy)

enter the required data and deploy.

Finally, add the bot you created on slack to your channel via `/invite @giggle-bot`

## Manual Deployment
### How to add Giggle bot
1. clone project
2. Set the Heroku env variable, `SLACK_TOKEN`, to your custom slack token (see how to get token above).
   `SLACK_TOKEN` is gotten from slack custom integration.
3. deploy project from Heroku.

### How to run locally
 - requires node.js
 - go to root folder
 - run  `npm install`
 - run  `SLACK_TOKEN=<token_from_slack> node index.js`

### How to contribute
 - fork repository
 - submit PR to `development` branch

### About this Project

This is a bot project created by the ChameleonOne Team of the Chingu-Chameleon Cohort.
The team members are [@Amanfojnr](https://github.com/amanfojnr), [@benjamin](https://github.com/benjaminadk) and [@afixoftrix](https://github.com/afixoftrix).
