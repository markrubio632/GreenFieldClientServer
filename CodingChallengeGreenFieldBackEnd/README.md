# CodingChallengeGreenFieldBackEnd

# Reminder
This is the Client server to be used alongside the Service server. If the Service is not properly configured, this client will not run. Please make sure to set-up the Service server correctly prior to attempting connectivity with this server.

## EnrolleeBackEnd - Client Server
EnrolleeBackEnd is a Java and Spring Boot Web application's backend. This application provides data manipulation from a MongoDB database in a RESTful manor, while applying a simple client-service Eureka Microservice. This project is treated as the server portion in the microserver architecture.

## POSTMAN Documentation and Example Usage
[POSTMAN DOCS](https://documenter.getpostman.com/view/11861886/TVRrV4QX)

## Installation
For proper set-up, several things will be needed: 
- MongoDB Server
- Eclipse (or similar IDE for Java development)
- Service Server which can be found [here](https://github.com/markrubio632/CodingChallengeGreenFieldBackEnd)

Please refer to the README for the Service server for installation and deployment of the Service. Once these applications are installed, ensure the two existing maven projects are imported into your workspace in the IDE.

### Database Configuration
Begin by creating your own MongoDB server. This can be either a localhost on a machine or using MongoDB Atlas, a cloud service provided by MongoDB. Once your server is properly configured to your liking, connect to the database by editing the application.properties file of this project to reflect your own database. Replace \<username\>, \<password\>, and \<DBAddress\> with your external MongoDB configuration.

## Deployment of Microservice
Please see the Service's deployment section and ensure that the Service server is running. Once it is, run this project and it will connect to the Eureka microservice. Commands can now be issued to request and retrieve information from the database.

## Testing Application
Please Refer to the POSTMAN Documentation and Example Usage above for example of commands and parameters to be given.
