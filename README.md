# Actions on Google: Interactive Fiction Sample using Node.js

This interactive fiction engine, is an app for the Google Assistant.

## Setup Instructions

### Steps for Actions SDK
1. Use the [Actions on Google Console](https://console.actions.google.com) to add a new project with a name of your choosing.
1. Under *Build a custom app*, click *BUILD* in the Actions SDK box.
1. Deploy this the `actionsdk.js` app to your preferred hosting environment
(we recommend [Google Cloud Functions](https://cloud.google.com/functions/docs/tutorials/http)).
1. Update the action package, action.json, with your endpoint URL.
1. Use the gActions CLI to complete the command shown in the Actions console.
1. Click *OK* in the Actions console.
1. Open the Simulator in the Actions console.
1. Type `Talk to my test app` in the simulator, or say `OK Google, talk to my test app` to any Actions on Google enabled device signed into your developer account.

### Steps for Dialogflow
1. Use the [Actions on Google Console](https://console.actions.google.com) to add a new project with a name of your choosing.
1. Under *Build a custom app*, click *BUILD* in the Dialogflow box and then click *Create Actions on Dialogflow*.
1. Click *Save* to save the project.
1. Click on the gear icon to see the project settings.
1. Select *Export and Import*.
1. Select *Restore from zip*. Follow the directions to restore from the InteractiveFiction.zip in this repo.
1. Deploy the `app.js` app to your preferred hosting environment (we recommend Google App Engine).
1. In the Fulfillment page of the Dialogflow console, enable Webhook, set the URL to the hosting URL, then save.
1. Open Dialogflow's Integrations page, open the Settings menu for Actions on Google, then click Test.
1. Click View to open the Actions on Google simulator.
1. Type `Talk to my test app` in the simulator, or say `OK Google, talk to my test app` to any Actions on Google enabled device signed into your developer account.

For more detailed information on deployment, see the [documentation](https://developers.google.com/actions/dialogflow/deploy-fulfillment).

## References and How to report bugs
* Actions on Google documentation: [https://developers.google.com/actions/](https://developers.google.com/actions/).
* If you find any issues, please open a bug here on GitHub.
* Questions are answered on [StackOverflow](https://stackoverflow.com/questions/tagged/actions-on-google).

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md.

## License
See LICENSE.md.

## Terms
Your use of this sample is subject to, and by using or downloading the sample files you agree to comply with, the [Google APIs Terms of Service](https://developers.google.com/terms/).

## Google+
Actions on Google Developers Community on Google+ [https://g.co/actionsdev](https://g.co/actionsdev).




C:\Users\rmw6165\Documents\Visual Studio Code\Projects\interactive-fiction-nodejs\interactive-fiction-nodejs>c:\Users\rmw6165\Downloads\gactions update --action_package action.json --project fictionexample