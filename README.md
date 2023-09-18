# Power-Platform-Global-AI-Hack
Hackathon2023

Visit the open source website to learn more where this is open to the to the entire community.
https://processsentinel.com/


## Installation & Custom Connector Setup Instructions

 - Download the attached solution "ProcessSentinel.Zip"
 - Import the solution into your environment
 - Edit the custom connector(s) using the swagger editor

### Azure OpenAI Custom Connector Configuration	 
 - Line 11 host, change out YOUR_NAME (Azure Name used during setup and deployment setup and configuration)
 - Line 18 chang out /YOUR_DEPLOYMENT (Azure Deployment Name)
 - Line 198 change out YOUR_KEY (Azure Service Key bound to this instance / deployment)
 - Line 204 change our YOUR_NAME (Azure Name used during setup and deployment setup and configuration)
 - Line 206 change our YOUR_NAME (Azure Name used during setup and deployment setup and configuration)
 - Line 288 change out /YOUR_DEPLOYMENT (Azure Deployment Name)
 - Close Swagger editor and now edit #3 Definition and edit the Authorization Policy and change out the YOUR_KEY for the header value

### OpenAI Direct Custom Connector Configuration
 - OpenAI direct
	 - Simply swap out the key. Edit #3 Definition and edit the Authorization Policy and change out the YOUR_KEY for the header value

### Canvas App Configuration
 - Edit the canvas application,edit the app on-start property and change the value of the variable Set(API,"OpenAI"); // set to "AzureOpenAI" or "OpenAI"


**With the custom connectors configured properly you should now be able to use the applicationassuming you have permium licensing**
