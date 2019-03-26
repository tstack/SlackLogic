# SlackLogic
SnapLogic app for Slack

## Install

1. Create an app in Slack (see https://api.slack.com/apps)
1. Install the Slack app in your Slack org
1. Create a project in SnapLogic
1. Create a REST Basic Auth Account in the new project
1. Checkout this repository into the new project
1. Create a Triggered Task for the _setup_ pipeline in the project
1. Go to the _setup_ task's details and open the URL in a web browser
1. Enter the requested information into the setup web page
1. Press "Finish Setup" and note the URL that is generated when the page finishes loading
1. Create a "Slash Command" in your Slack app with the name "/checkout-project"
1. Copy the URL from the setup task page into "Request URL" field in the slash command settings
