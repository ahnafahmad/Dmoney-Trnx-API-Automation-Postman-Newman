# Dmoney-Trnx-Api-Automation-Newman

## Technology and Tools used in this Project
 - Postman
 - Newman
 
 ## Project Scenarios
 - The system admin can login to the sytem
 - Customer can Create Id
 - Customer can get Id
 - Agent can Create Id
 - Agent can get Deposit money from system
 - Agent can Check Balance
 - Agent can Deposit to Customer
 - Customer can Check Balance
 - Customer can withdraw money
 - Customer (Sender) can send money to another Customer ( Receiver)
 
 ## How to run this project:
 - Clone this project
 - hit the following command:
  ```
 npm i
 ```
 ```
 npm test
```
 
 ## How to Generate Report: 
 Automated dmoney API using Postman where test cases are added for Login,Creating users,Searching users and performed testing for CRUD operations. 
 Steps to run this project:
 - Give the following commands by opening terminal in the project folder to create newman Report:
```
 npm i newman
 ```
 ```
 npx newman run .\collection\Dmoney_Users_collection.json -e -n 1
```
```
npm i newman-reporter-htmlextra
```
```
node .\report.js
```

## Prerequisite
  - Node.js must be installed
  
## API documentation
- Link: shorturl.at/jpTYZ

## Newman Automation Report Image
  ![Newman Automation report](https://user-images.githubusercontent.com/58990500/192164259-a75c10f2-8bbe-4c4f-bf83-41bca42aee16.PNG)
