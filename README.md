<h1 align="center" style="border-bottom: none;">:rocket: IBM Digital Tech Tutorial: Voice Agent</h1>
<h3 align="center">In this hands-on tutorial you will create a new Voice Agent with Watson on the IBM Cloud that can listen and respond directly to customers using natural language over the telephone.</h3>

## Prerequisites

1. Sign up for an [IBM Cloud account](https://cloud.ibm.com/registration).
2. Fill in the required information and press the „Create Account“ button.
3. After you submit your registration, you will receive an e-mail from the IBM Cloud team with details about your account. In this e-mail, you will need to click the link provided to confirm your registration.
4. Now you should be able to login to your new IBM Cloud account ;-)

## Configuring the Voice Agent on the IBM Cloud

<h4>1) Create the Voice Agent & additional services</h4>
After the login you will see your IBM Cloud Dashboard. In the upper menu bar click Catalog. In the Catalog section, search for "Voice Agent" and click on it. Select Dallas as the region and use the Lite Plan. Click "Create".
Repeat this process to create three additional services: 

1. Watson Assistant
2. Speech to Text and
3. Text to Speech.

For these services select the region of your choice and the Lite Plan.

![Catalog Voice Agent](readme_images/catalog-voice-agent.png)

<h4>2) Import json to your Watson Assistant</h4>
Create a new Skill and choose Dialog Skill, then select Import Skill and upload either the skill-banking-balance-enquiry.json or the skill-pizza-order-book-table.json. You will see the intents, entities and the dialog. To learn more about these and the Watson Assistant click <a href="https://github.com/FelixAugenstein/digital-tech-tutorial-watson-assistant">here</a>.


![Import JSON File](readme_images/import-json-skill.png)
