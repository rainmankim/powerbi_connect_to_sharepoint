# Establishing Live PowerBI with Excel on Sharepoint 
<img align="right" src="https://user-images.githubusercontent.com/62319355/110085335-efcdb100-7dcb-11eb-9e9b-77f2849154a8.png" width="220" height="80" alt="Excel logo">
:smile: :grinning: :sleepy: :relieved: :confused: :open_mouth: :astonished: :thumbsup:


```
There are 3 main ways in which you can connect to Sharepoint Data:
Option 1. Connect from PowerBI to Sharepoint directly
Option 2. Connect from PowerBI to Sharepoint Excel
Option 3. Connect from PowerBI to synced OneDriver Folder (need personal Gateway to allow refresh on PowerBI Web)
```

#### Before you proceed, you might want to clear existing permissions.
#### This is because if you have previously attempted to establish connection and failed, you need to delete your previous configuration
<img align="center" src="https://user-images.githubusercontent.com/62319355/127885748-1f6857da-7a8c-4fe5-b2ad-1bca3b922bb4.png" width="450"  alt="Excel logo">

#### If you see an error message as shown above, you can clear data source settings by following the steps below
<img align="center" src="https://user-images.githubusercontent.com/62319355/127885756-34cc61f6-1cff-498a-a1e2-c70dcfb2f92f.png" width="450"  alt="Excel logo">
<img align="center" src="https://user-images.githubusercontent.com/62319355/127885767-ec8412ff-5e66-4274-b56a-ba7569bdb6e9.png" width="450"  alt="Excel logo">

Now let us return to the main topic


# Option 1. Connect from PowerBI to Sharepoint directly
<img align="center" src="https://user-images.githubusercontent.com/62319355/127896639-535fc2c7-41e1-4af7-97c4-a89b3b0e409c.PNG" width="450"  alt="Excel logo">
<img align="center" src="https://user-images.githubusercontent.com/62319355/127897308-fb5b4786-2a7d-44ed-8c49-236cf9902848.PNG" width="450"  alt="Excel logo">
<img align="center" src="https://user-images.githubusercontent.com/62319355/127898969-21b1ef7a-57ef-42f9-8f04-50e1266d5b27.PNG" width="550"  alt="Excel logo">

<img align="center" src="https://user-images.githubusercontent.com/62319355/127944551-fc5454f9-5d35-45f5-bfb8-1dcbe4bb7055.PNG" width="550"  alt="Excel logo">

<img align="center" src="https://user-images.githubusercontent.com/62319355/127943886-4230bb12-dcd5-48f6-b819-11972610ee6f.PNG"   alt="Excel logo">
<img align="center" src="https://user-images.githubusercontent.com/62319355/127943888-d6fe1923-16b7-4efe-ba14-0175f95e0839.PNG"   alt="Excel logo">



# Option 2. Connect from PowerBI to Sharepoint Excel

```
For option 2(connect PowerBi to Excel file on Sharepoint), follow the steps below

(1) Upload an excel file on SharePoint
(2) Copy Path URL Link from details tab (refer to red circles in the picture)
(3) Open PowerBI, select connect to data via Web
    Paste Path URL in Web box, be sure to remove any tailing characters beyond .xlsx extension
(4) Upon connection set up, sign in using organizational account
(5) Create Report, and publish to PowerBI Web
(6) Open PowerBI Web and select Database related to Dashboard and enter the Database's settings
    Update user credentials for access to Web using OAuth2 and sign in using org.
    Update scheduling refresh per requirement and save
 For more details, refer to https://www.youtube.com/watch?v=YI6ey8EvIAI
```
<img align="center" src="https://user-images.githubusercontent.com/62319355/127948129-48a5ae28-63b1-4347-853a-428d9993de1c.PNG"   alt="Excel logo">


# Option 3. Connect from PowerBI to synced OneDriver Folder

```
Option 3 is a simple process.
On your OneDrive, click on "Sync".
```
<img align="center" src="https://user-images.githubusercontent.com/62319355/127945680-c8dbdfcb-cc92-45f0-b493-c1688ec8e24f.PNG"   alt="Excel logo">


#### Once OneDrive Folders are synced on your laptop, connect to your target folder/file as you would do for other files.
--------------------------------------------------------------------------------------------------------------------------------------------------






🎈🦾 😎 That's it from me. 
```
Author: Ray Kim
https://www.linkedin.com/in/rainmankim/
```
--------------------------------------------------------------------------------------------------------------------------------------------------
