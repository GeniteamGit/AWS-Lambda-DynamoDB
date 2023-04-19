# AWS LAMBDA FUNCTIONS DYNAMODB </br>
## Description </br>
Hey there 👋, This is a simple aws lambda function for adding, deleting, editing and getting data from dynamoDb . In these directories you will find the code for the aws lambda function apis. These are basic functions to perform single actions on the dynamoDb database using lambda functions </br>
 </br>
## Tech Stack </br> 
AWS Lambda  </br>
Node JS </br>


### directory Structure . </br>
├── controllers/ </br>
│ ├── scores </br>
│ ├── teams </br>
│ ├── templates </br>
│ ├── user </br>
│ ├── worspaces </br>
├──db/ </br>
│ ├── Dao/ </br>
│ │ └── messages.js </br>
│ │ └── scores.js </br>
│ │ └── taskDao.js </br>
│ │ └── teamsDao.js </br>
│ │ └── templatesDao.js </br>
│ │ └── workspaceDao.js </br>
│ ├── models/ </br>
│ │ └── game.js </br>
├── services/ </br>
│ ├── validations/ </br>
│ │ └── playerValidation.js </br>
│ │ └── socketValidation.js </br>
│ │ └── tournamnetManagmentValidation.js </br>
│ │ └── validationMatch.js </br>
│ │ └── validationMeeting.js </br>
│ │ └── validationMessages.js </br>
│ │ └── validationStream.js </br>
│ │ └── validationTournament.js </br>
│ │ └── validationUser </br>
│ ├── API_RESPONSES.JS </br>
│ ├── checkRequiredFields.js </br>
│ ├── constants.js </br>
│ ├── helpers.js </br>
│ ├── publicServices.js </br>
│ └── webSocketMessage.js </br>
├──README.md </br>
 </br>
 </br>
 </br>
 
# Installation </br>

### NodeVersion--->12  </br>

### npm i  </br>
 </br>

# starting Command
### npm run offline 
 </br>
 </br> 

Make sure to include secret keys and access key where ever is needed in project like in config.json and constants.js file. 






