# Mycroft-Slack-skill
Mycroft will speak with Slack !

This skill allows to send messages on Slack

To get this done we need
  - Add the app `Incoming Webhooks` to the team wanted on Slack.
  - Add `"SlackSkill": {
    "incoming_webhook_url": "TXXXXXXXX/BXXXXXXXX/XXXXXXXXXXXXXXXXXXXXXXXX"
  }` in the [mycroft config file](https://docs.mycroft.ai/skills.and.features/config) (Replace with the end of the URL provided by the incoming webhook app)


## Current state

Working features:
 - `Send <my message> on Slack` Send <my message> on slack !

Known issues:

TODO:
 - Adds vocal feedback ("sending <my message>")
 - Adds channel selection
 - Adds getting last messages on specific channel
