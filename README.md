# zabbix-teams-webhook
## Preface
This script was created to meet the needs of my workplace. It does nothing more and nothing less then what we needed. Howerver, I tried to make it as flexible as I can.
I may or may not update and improve it.
## Installation
1. Get Microsoft Teams Webhook URL. Save it for next step.

   Microsoft already made a guide how to do this [here](https://docs.microsoft.com/en-us/microsoftteams/platform/webhooks-and-connectors/how-to/add-incoming-webhook).
2. Import media type into Zabbix.

   Go to **Administration** > **Media types** > Press **Import** > Choose File *media_teams.xml* > Press **Import**
3. Configure media type

   Go to **Administration** > **Media types** > Select *Microsoft Teams*
   
   Change values in the *teamsURL* field with the webhook URL created in the first step, and *zabbixURL* with your Zabbix URL (including `https://` and trailing `/`) - this one is required for buttons in notification to work)
   
## To-do
- [ ] Complete installation instruction
- [ ] Everything else
