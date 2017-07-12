# Interactive messages and rich formatted messages in Slack

This Slackbot is ready to be deployed in [Beepboop](https://beepboophq.com) as a Slack App and shows how interactive messages work and some rich formatting options available in Botkit. It belongs to the sixth part of a series of tutorials about Slackbots.

You can follow the [tutorial](http://sitepoint.com) to build this application or jump straight to the code.

# Requirements
- A Slack account with administrative privileges.
- A Wit.ai account.
- A [Beepboop](https://beepboophq.com) account with permissions to your Github repositories.
- [Node.js](https://nodejs.org/en/download/) version 5 or higher.

# Installation
1. Fork this repository into your own Github account.
2. Go to https://wit.ai/ and create a new app by importing `NumberBotApp.zip`.
3. Once the app is created, wait a few seconds and check if the circle next to the app name becomes green. As Wit.ai is still in beta, sometimes this doesn't happen, so go to the Settings tab to delete the app and create it again. You may have to do this a few times before the app shows a green status.
4. Once the app is created correctly, go to the Settings tab and generate a Server Access Token if none is shown by clicking the *Reset Token* icon.
5. Create a new Beepboop project with your forked repository.
6. Follow the instructions to create an Slack app with a bot user and link it to your Beepboop project.
7. Configure a Slash Command in your Slack app.
8. Enable Interactive Messages.
9. In Beepboop, go to the *Settings* tab in your project and enable *Multi-Team Socket Mode*. Also, on this page, enter your Wit.ai token
10. Make a commit to some file of the project to start the building process.
11. On Beepboop start your bot on the *Status* tab.
12. Go to the page of your bot at [https://beepboophq.com/bots/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx>](https://beepboophq.com/bots/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx), where `xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx` is the ID of your project, and install the Slack app in one of your Slack teams. 
13. Play with the bot by sending a message with a number, asking for a trivia with a direct message, or executing the slash command.

# License
MIT