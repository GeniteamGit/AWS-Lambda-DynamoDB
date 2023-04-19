# AWS LAMBDA FUNCTIONS DYNAMODB </br>
## Introduction </br>
Hey there 👋, This is a simple aws lambda function for adding, deleting, editing and getting data from dynamoDb . In these directories you will find the code for the aws lambda function apis. These are basic functions to perform single actions on the dynamoDb database using lambda functions </br>
 </br>
 
## Description </br>
This is a sample package.json file for a Node.js-based project called VSpace. It includes dependencies for popular Node.js modules such as Axios, Nodemailer, Sequelize, and Validator, as well as dev dependencies for testing with Mocha and Chai. The project uses the Serverless Framework for building serverless applications and includes plugins for running the application offline and pruning unused resources during deployment. The package.json file can be used as a starting point for building Node.js-based applications with similar dependencies and technologies.
</br>
This project serves as a foundation for developing a human resource management system for a software house. The system will likely involve serverless functions, API calls to other services, and a database for storing employee data.</br>
</br>
By using this project, the development team can ensure that the project has the necessary dependencies to implement key functionality, such as sending emails with Nodemailer, making HTTP requests with Axios, and validating user input with Validator.</br>
</br>
The dev dependencies for Mocha and Chai enable the team to write and run automated tests to ensure that the system is functioning correctly. Additionally, the nodemon package can be used during development to automatically restart the server when changes are made to the code.</br>
</br>
With the Serverless Framework, the team can easily deploy and manage the application on a cloud platform such as AWS Lambda, Azure Functions, or Google Cloud Functions. The serverless-offline plugin allows the team to test and debug the application locally before deploying it to the cloud, while the serverless-prune-plugin helps to optimize resource usage and reduce costs.</br>
</br>
Overall, this project provides a solid foundation for building a scalable and efficient human resource management system for a software house.</br>
</br>
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






