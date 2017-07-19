# Giggle Bot
What is giggle bot?
Giggle bot is a slack bot that increases the humor levels of your slack chat room. It does this by reading trigger words from the slack channel through the slack api and returning a joke or a meme-ish picture (depending on the input).

## Automatic Deployment

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Manual Deployment
### How to add Giggle bot
1. clone project
2. Set the heroku env variable, `SLACK_TOKEN`, to your custom slack token.
   `SLACK_TOKEN` is gotten from slack custom integration.
3. deploy project from heroku.

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
