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
 - `Send <my message> on Slack` Send <my message> on slack !

Known issues:

TODO:
 - Adds vocal feedback ("sending <my message>")
 - Adds channel selection
 - Adds getting last messages on specific channel
