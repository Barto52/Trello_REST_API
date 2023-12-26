# Trello REST API with Postman and CI/CD configuration (Newman + Jenkins)
## ℹ️ About the repository
<p align="jusify">This repository was created for the purpose of picturing my knowledge of Postman and also CI/CD basics.<br>
The attached collection thoroughly examines Trello key functionalities, leveraging dynamic variables. <br>
Further details below👇</p>

## 🗃️ Test scope
Test scope is based on <a href="https://developer.atlassian.com/cloud/trello/rest/api-group-actions/#api-group-actions" target="_blank">Trello REST API documentation:</a>

<details>
  <summary>Board</summary>

  - Create a Board
  - Create a Label on a Board
  - Get a Board
  - Update a Board
</details>

<details>
  <summary>List</summary>
  
  - Create a List on a Board
  - Get a List
  - Update a List
</details>
  
<details>
  <summary>Card</summary>
  
  - Create a new Card
  - Create a new Label on a Card
  - Get a Card
  - Add a new comment to a Card
  - Update a Card
</details>

<details>
  <summary>Checklist</summary>
  
  - Create a Checklist
  - Get a Checklist
  - Create a Checkitem on a Checklist
  - Update a CheckItem on a Card
  - Get Checkitems on a Checklist
</details>
    
<details>
  <summary>Delete</summary>
  
  - Delete a Checkitem from Checklist
  - Get Checkitems on a Checklist
  - Delete a Checklist
  - Get a Checklist
  - Delete a Card
  - Get a Card
  - Delete a Board
  - Get a Board
</details>
 
## 🚀 How to run the collection?
1️. [Postman installation](#postman-installation)

2️. [Creating a Trello account](#creating-trello-account)

3️. [Authentication](#authentication)
  
4️. [Collection importing into Postman](#collection-import)
  
5️. [Running collection and tests](#running-collection)
  
#### <a name="postman-installation"> ⚙️ Postman installation</a>
1. Visit the [Postman Official Website](https://www.postman.com/). Click on the logo corresponding to your operating system.
2. Download the installation file.
3. Run the installer and follow the instructions.

#### <a name="creating-trello-account"> 💻 Creating a Trello account</a>
1. Navigate to the [Trello Official Website](https://www.trello.com/).
2. Click on "Get Trello for free" and create an account.
3. Check your email to confirm your new Trello account.
4. You are ready to use Trello!

#### <a name="authentication"> 🔑 Authentication</a>
1. Log in to your Trello account.
2. Go to [Trello developer API key page](#https://trello.com/app-key) and click on "Go to the Power-Up Admin Portal".
3. Click on "New" button and enter the required data.
4. Click on "Generate new API key" - your API key will be displayed on the page. Save it for later use.
5. Click on "Token" link and allow to access to your account.
6. Your token will be displayed on the page. Save it for later use.

#### <a name="collection-import"> 📂 Collection importing into Postman</a>
1. Download [the collection](#https://github.com/Barto52/Trello_REST_API/blob/main/Trello%20API%20BART.postman_collection.json).
2. Go to Postman app. On the left sidebar click on "Import" button.
3. Drag and drop the downloaded collection or select it from Postman app.
4. Now you are ready to use it!

#### <a name="running-collection"> ▶️ Running collection and tests</a>
1. Click on "Trello API BART" collection and click on "Variables".
2. Paste your API Key in "Current value" for "APIKey" variable and your token in "Current value" for "Token" variable.
3. Save the changes.
4. Now it is time to run the collection! Select "Trello API Bart" and click on "Run". Alternatively right click on collection and choose "Run collection".
5. Ensure all requests are selected. If not, select "Select All" and click on "Run Trello API BART".
6. If all requests pass (green color) - CONGRATS!🎊 Expected output below: <br> ![image](https://github.com/Barto52/Trello_REST_API/assets/131921596/8038dd3c-c918-4add-a67e-09072b6360b1)

## 🔁CI/CD configuration with Newman and Jenkins
<p align="jusify">The Postman collection can also be run in a CI/CD pipeline. Newman and Jenkins were used for this purpose.
Scroll down for more details 👇</p>

## 🚀How to install Newman nad Jenkins and prepare the pipeline?
1️. [Newman installation](#newman-installation)

2️. [Docker installation](#docker-installation)

#### <a name="newman-installation"> ⚙️ Newman installation</a>
1. Install Node.js on your computer. Go to [Node.js website](#https://nodejs.org/en) and download LTS version. Run installation file.
2. Open terminal window and type ```node --version```. Installed version should be displayed on your screen.

