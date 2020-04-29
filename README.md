# atlassian-sdk-slack
An Atlassian SDK Slack Integration that uses the Slack Apps + Atlassian SDK

The goal of this project:
1. Use the new Slack API to build appropriate "slash" commands to forward to:
   1. An Atlassian SDK Java plugin (JIRA, Confluence, Bitbucket, etc) that would host the URLs for the Slash commands to be sent to (hosted by the Atlassian server application itself)
   1. A public accessible URL that can be run independently by a bot program which then interacts with said Atlassian server
1. Use OAuth to authorize on a per user basis both from Slack and the Atlassian app/suite in question and/or via SSO.
1. Respond to events in a Slack fashion (prompts, dialogs, etc)
