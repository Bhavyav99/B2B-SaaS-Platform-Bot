## B2B-SaaS-Platform-Bot
IBM Watson Assistant Platorm 

#Step 1: Create a Watson Assistant skill

Prerequisite:Sign up for [IBM Cloud](https://cloud.ibm.com/registration/) if you don't have an IBM Cloud account yet.
Use one or both of these options (with or without BAE) to setup an Assistant skill.

You can find rent_a_car.json file in the location 

his file will be imported while creating the Watson Assistant skill. Below section will details the steps involved in importing the skills.
Create the service by following this link and hitting Create:
* [**Watson Assistant**](https://cloud.ibm.com/catalog/services/watson-assistant)
Select the Free plan and give a meaning full name in the service name field as shown below

Import the Assistant rent_a_car.json:

* Find the Assistant service in your IBM Cloud Dashboard.
* Click on the service and then click on `Launch Watson Assistant`.
* Go to the `Skills` tab.
* Click `Create skill`
* Click the `Import skill` tab.
* Click `Choose JSON file`, go to your cloned repo dir, and `Open` the rent_a_car.json file in [`data/assistant/rent_a_car.json`](data/assistant/rent_a_car.json).
* Click `Import`.
