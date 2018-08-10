# Fetch data from Google spreadsheet using JavaScript 

Download or copy code of index.html and add credentials, In console you will see the array of Rows and Columns from Spreadsheet.

### Get all credentials
Go to https://docs.google.com/spreadsheets/u/0/ and select your spread sheet that you want to fetch and copy the spread sheet id from the link.

Go to https://console.developers.google.com/ and sign in with gmail account

Create a new project

Go to crendentials tab and click on create crendentials button and select API key button and copy your API Key.

Go to library tab and search for Google Sheets API and click on enable
Go back to https://console.developers.google.com/ and go to credentials tab and click on create crendentials button then select Google
Sheets API from first drop down (Which API are you using).

Select Web browser (Javascript) fron second drop down (Where will you be calling the API from?).

Select User Data button (radio button) from (What data will you be accessing?) Section, Click on What crendentials do i need? button.

Enter basic details of project 

Name : PROJECT_NAME

Authorized JavaScript origins : LINK_OF_YOUR_WEBSITE_WITHOUT_ANY_SUBDIRECTORY

And click on Create OAuth client ID button

Copy the client ID 
Paste the all credentials in file and run.


### Contributors
  - Salman <salmanmemon569@yahoo.com>
