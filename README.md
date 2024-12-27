This repository shows how to connect to a google drive in order to download, upload, or modify folders

# Setting up a google account to be able to access its drive 

Following this tutorial : https://developers.google.com/drive/api/quickstart/python 
   1. Create a google cloud project for the account
   2. Enable the google drive api here : https://console.cloud.google.com/apis/enableflow?apiid=drive.googleapis.com
   3. Configure the OAuth consent screen: https://console.cloud.google.com/apis/enableflow?apiid=drive.googleapis.com
   4. Authorize credentials for the desktop app: https://console.cloud.google.com/apis/enableflow?apiid=drive.googleapis.com
   5. CRUCIAL: before running the code, make sure to enable the user as described in the top answer for this stack overflow question: https://stackoverflow.com/questions/75454425/access-blocked-project-has-not-completed-the-google-verification-process
   6. Install the client library requirements and verify the setup code is working and enables user.


