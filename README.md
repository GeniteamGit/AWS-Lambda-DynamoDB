firebase-javascript
Description
Hey there 👋, This is a simple aws lambda function for adding, deleting, editing and getting data from dynamoDb . In these directories you will find the code for the aws lambda function apis. These are basic functions to perform single actions on the dynamoDb database using lambda functions

Tech Stack

Admin SDK
AWS Lambda 
Node JS


### directory Structure .
├── controllers/
│ ├── scores
│ ├── teams
│ ├── templates
│ ├── user
│ ├── worspaces
├──db/
│ ├── Dao/
│ │ └── messages.js
│ │ └── scores.js
│ │ └── taskDao.js
│ │ └── teamsDao.js
│ │ └── templatesDao.js
│ │ └── workspaceDao.js
│ ├── models/
│ │ └── game.js
├── services/
│ ├── validations/
│ │ └── playerValidation.js
│ │ └── socketValidation.js
│ │ └── tournamnetManagmentValidation.js
│ │ └── validationMatch.js
│ │ └── validationMeeting.js
│ │ └── validationMessages.js
│ │ └── validationStream.js
│ │ └── validationTournament.js
│ │ └── validationUser
│ ├── API_RESPONSES.JS
│ ├── checkRequiredFields.js
│ ├── constants.js
│ ├── helpers.js
│ ├── publicServices.js
│ └── webSocketMessage.js
├──README.md/



Installation
npm i 

