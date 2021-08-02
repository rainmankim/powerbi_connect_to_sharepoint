# Establishing Live PowerBI with Excel on Sharepoint 
<img align="right" src="https://user-images.githubusercontent.com/62319355/110085335-efcdb100-7dcb-11eb-9e9b-77f2849154a8.png" width="220" height="80" alt="Excel logo">
:smile: :grinning: :sleepy: :relieved: :confused: :open_mouth: :astonished: :thumbsup:



```
Author: Ray Kim
Contact: rainmankim@gmail.com
```

```
There are 3 main ways in which you can connect to Sharepoint Data:
Option 1. Connect from PowerBI to Sharepoint directly
Option 2. Connect from PowerBI to Sharepoint Excel
Option 3. Connect from PowerBI to synced OneDriver Folder
```

### Step 0. TTTTTTTTTTTTTTTTTTTTTTTTTT
Please download the latest version of ODBC Driver <br/>
https://www.cloudera.com/downloads/connectors/hive/odbc/2-6-1.html

#### Once eeeeeeeeeeeeeeeeeeeeeeee
<img align="center" src="https://user-images.githubusercontent.com/62319355/121278485-3f5cd500-c905-11eb-8c89-77172cc2ad13.png" alt="ODBC_set_up">

#### CCCCCCCCCCCCCCCCCCCCCCCCCCCCC
<img align="center" src="https://user-images.githubusercontent.com/62319355/121278560-6c10ec80-c905-11eb-983b-662b62110897.png" alt="SSL_enable">






```
This is for laterrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrr
In this repository, I am going to show you how to connect PowerBi to Excel file on Sharepoint in your organization.
I will illustrate this in the following steps.
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








🎈🦾 😎 That's it from me. 
--------------------------------------------------------------------------------------------------------------------------------------------------
