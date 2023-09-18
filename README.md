# Power-Platform-Global-AI-Hack
Hackathon2023

Visit the open source website to learn more where this is open to the to the entire community.
https://processsentinel.com/


## Instructions

 - Download the attached solution "ProcessSentinel.Zip"
 - Import the solution into your environment
 - Edit the custom connector(s) using the swagger editor
	 - Azure OpenAI (prefered)
		 - Line 11 host, change out YOUR_NAME
		 - Line 18 chang out /YOUR_DEPLOYMENT
		 - Line 198 change out YOUR_KEY
		 - Line 204 change our YOUR_NAME
		 - Line 206 change our YOUR_NAME
		 - Line 288 change out /YOUR_DEPLOYMENT
		 - Close Swagger editor and now edit #3 Definition and edit the Authorization Policy and change out the YOUR_KEY for the header value
	 - OpenAI direct
		 - No need to configure for this demo unless you want, simply swap out the key. Edit #3 Definition and edit the Authorization Policy and change out the YOUR_KEY for the header value
	 - Edit the canvas application,edit the app on-start property and change the value of the variable Set(API,"OpenAI"); // set to "AzureOpenAI" or "OpenAI"


**With the custom connectors configured properly you should now be able to use the applicationassuming you have permium licensing**
