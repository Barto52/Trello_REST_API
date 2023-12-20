# Trello_REST_API with Postman
## ℹ️ About the repository
<p align="jusify">This repository was created for the purpose of picturing my knowledge of Postman.<br>
The attached collection checks the most important Trello functionalities using dynamic variables. <br>
More information below👇</p>

## 🔎Test scope
Test scope is based on <a href="https://developer.atlassian.com/cloud/trello/rest/api-group-actions/#api-group-actions" target="_blank">Trello REST API documentation:</a>
- **Board**
  - Create a Board
  - Create a Label on a Board
  - Get a Board
  - Update a Board
- **List**
  - Create a List on a Board
  - Get a List
  - Update a List
- **Card**
  - Create a new Card
  - Create a new Label on a Card
  - Get a Card
  - Add a new comment to a Card
  - Update a Card
- **Checklist**
  - Create a Checklist
  - Get a Checklist
  - Create a Checkitem on a Checklist
  - Update a CheckItem on a Card
  - Get Checkitems on a Checklist
- **Delete**
  - Delete a Checkitem from Checklist
  - Get Checkitems on a Checklist
  - Delete a Checklist
  - Get a Checklist
  - Delete a Card
  - Get a Card
  - Delete a Board
  - Get a Board
 
## 🚀 How to run the collection?
:one: [Postman installation](#one)
  
:two: [Creating a Trello account](#two)
  
:three: [Authentication](#three)
  
:four: [Collection importing into Postman](#four)
  
:five: [Running collection and tests](#five)
  
#### <a name="one"> ⚙️ Postman installation</a>

1. Go to the [Postman Official Website](https://www.postman.com/). Click on a logo of your operating system.
2. Download the installation file.
3. Run the installer and follow the instructions.

#### <a name="two"> 💻 Creating a Trello account</a>
1. Go to [Trello Official Website](https://www.trello.com/).
2. Click on "Get Trello for free" and create an account.
3. Check your email to confirm your new Trello account.
4. You are ready to use Trello!

#### <a name="three"> 🔑 Authentication</a>
1. Log in to your Trello account.
2. Go to [Trellod developer API key page](#https://trello.com/app-key) and click on "Go to the Power-Up Admin Portal".
3. Click on "New" button and enter the required data.
4. Click on "Generate new API key" - your API key will be displayed on the page. Save it for later use.
5. Click on "Token" link and allow to access to your account.
6. Your token will be displayed on the page. Save it for later use.

#### <a name="four"> 📂 Collection importing into Postman</a>
1. Download [my collection](#https://github.com/Barto52/Trello_REST_API/blob/main/Trello%20API%20BART.postman_collection.json).
2. Go to Postman app. On the left sidebar click on "Import" button.
3. Drag and drop downloaded collection or select it from Postman app.
4. Now you are ready to use it!

#### <a name="five"> ▶️ Running collection and tests</a>
1. Click on "Trello API BART" collection and click on "Variables".
2. Paste your API Key in "Current value" for "APIKey" variable and your token in "Current value" for "Token" variable.
3. Save the changes.
4. Now it is time to run the collection! Select "Trello API Bart" and click on "Run". Alternatively right click on collection and choose "Run collection".
5. All requests have to be selected. If they are not, select "Select All" and click on "Run Trello API BART".
6. If all requests passed (green color) - CONGRATS!🎊 Expected output below: <br> ![image](https://github.com/Barto52/Trello_REST_API/assets/131921596/8038dd3c-c918-4add-a67e-09072b6360b1)
