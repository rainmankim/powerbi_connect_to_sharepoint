# Establishing Live PowerBI with Excel on Sharepoint 
<img align="right" src="https://user-images.githubusercontent.com/62319355/110085335-efcdb100-7dcb-11eb-9e9b-77f2849154a8.png" width="220" height="80" alt="Excel logo">
:smile: :grinning: :sleepy: :relieved: :confused: :open_mouth: :astonished: :thumbsup:





```
There are 3 main ways in which you can connect to Sharepoint Data:
Option 1. Connect from PowerBI to Sharepoint directly
Option 2. Connect from PowerBI to Sharepoint Excel
Option 3. Connect from PowerBI to synced OneDriver Folder
```

#### Before you proceed, you might want to clear existing permissions.
#### This is because if you have previously attempted to establish connection and failed, you need to delete your previous configuration
<img align="center" src="https://user-images.githubusercontent.com/62319355/127885748-1f6857da-7a8c-4fe5-b2ad-1bca3b922bb4.png" width="450"  alt="Excel logo">
#### If you see an error message as shown above, you can clear data source settings. 
<img align="center" src="https://user-images.githubusercontent.com/62319355/127885756-34cc61f6-1cff-498a-a1e2-c70dcfb2f92f.png" width="450"  alt="Excel logo">


# Option 1.Connect from PowerBI to Sharepoint directly


Please download the latest version of ODBC Driver <br/>
https://www.cloudera.com/downloads/connectors/hive/odbc/2-6-1.html

#### Once eeeeeeeeeeeeeeeeeeeeeeee
<img align="center" src="https://user-images.githubusercontent.com/62319355/121278485-3f5cd500-c905-11eb-8c89-77172cc2ad13.png" alt="ODBC_set_up">





# Option 2. Connect from PowerBI to Sharepoint Excel

```
For option 2(connect PowerBi to Excel file on Sharepoint), follow the steps below

(1) Upload an excel file on SharePoint
(2) Copy Path URL Link form excel "Info" tab of excel sheet
(3)	Open PowerBI, select connect to data via Web
	  Paste Path URL in Web box, be sure to remove any tailing characters beyond .xlsx extension
(4) Upon connection set up, sign in using organizational account
(5) Create Report, and publish to PowerBI Web
(6) Open PowerBI Web and select Database related to Dashboard and enter the Database's settings
	  Update user credentials for access to Web using OAuth2 and sign in using org.
	  Update scheduling refresh per requirement and save

```

# Option 3. Connect from PowerBI to synced OneDriver Folder







🎈🦾 😎 That's it from me. 
```
Author: Ray Kim
https://www.linkedin.com/in/rainmankim/
```
--------------------------------------------------------------------------------------------------------------------------------------------------
