# Mycroft-Slack-skill
Mycroft will speak with Slack !

This skill allows to send messages on Slack

To get this done we need
  - Add an incoming webhook to the team wanted
  - Write `"SlackSkill": {
    "incoming_webhook_url": "TXXXXXXXX/BXXXXXXXX/XXXXXXXXXXXXXXXXXXXXXXXX"
  }` (Replace with the end of the URL provided by the incoming webhook app)


## Current state

Working features:
 - `Send ... on Slack` Send fixed message on Slack

Known issues:

TODO:
 - Add regexp to send what user wants !
