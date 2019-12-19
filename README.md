# Connecting Salesforce to Slack through Tray.io
By connecting `Salesforce` with `Slack`,
using the `Tray.io` platform, notification can be send to the relevant Slack Channel when  new opportunities are created in Salesforce. The data used to created the new opportunity in Salesforce will be send to a workflow on the Tray platform as webhook. 

Using a conditional operator, the country of which the opportunity is located can be sorted out. Then the data will be mapped into the correct format and an API request will be made to the Slack API. Finally, notification with the opportunity inforamtion will be sent to the relevant Slack channel.
