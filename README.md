## B2B-SaaS-Platform-Bot
IBM Watson Assistant Platorm 

### Step 1: Create a Watson Assistant skill

Prerequisite:Sign up for [IBM Cloud](https://cloud.ibm.com/registration/) if you don't have an IBM Cloud account yet.
Use one or both of these options (with or without BAE) to setup an Assistant skill.

You can find skill-Chat_Bot.json file in the repository, this file will be imported while creating the Watson Assistant skill. 
Below section will details the steps involved in importing the skills.

Create the service by following this link and hitting Create:
* [**Watson Assistant**](https://cloud.ibm.com/catalog/services/watson-assistant)
Select the Free plan and give a meaning full name in the service name field as shown below

Import the Assistant skill-Chat_Bot.json:

* Find the Assistant service in your IBM Cloud Dashboard.
* Click on the service and then click on `Launch Watson Assistant`.
* Go to the `Skills` tab.
* Click `Create skill`
* Click the `Import skill` tab.
* Click `Choose JSON file`, go to your cloned repo dir, and `Open` the rent_a_car.json file in [`data/assistant/rent_a_car.json`](data/assistant/rent_a_car.json).
* Click `Import`.

Note: you can change the dialog systems as required and the json file will be modified accordingly. 

## Integration 

* Find the Assistant service in your IBM Cloud Dashboard.
* Click on the service and then click on `Launch Watson Assistant`.
* Go to the `Assistant` tab.
* Click `Create Assistant`
* Type the Assistant name and click on create 
* Select `Add diaog Skill` and choose the skill created. 
* The assistant is created 
* In the right Column, create `Webchat` integration and choose the 
  UI style and other options necessary. 
* Also, Add Preview `Link Integration`, where a link will be shown to try it out and share with others. 

## Output or the Preview Link 

* [**Preview Link**](https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=au-syd&integrationID=b6e32f7f-3a6d-4f51-b6b6-48d57e25e3bd&serviceInstanceID=595b2130-11fb-4a6e-85d7-e6c20300185b)
