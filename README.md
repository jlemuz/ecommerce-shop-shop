# ecommerce-shop-shop

## Description  
The purpose of this project was implement Sequelize to perform CRUD operations and test with Imsomnia.

## Technologies Used  
- mysql2: Create the sql database
- Sequelize: Connect Express.js to MySQL database
- dotenv: Create environment variables to store sensitive data (database credentials)  
    - .env file is created with database credentials
    - .env file should be added to the .gitignore in order to prevent credentials from being pushed to GitHub
- Insomnia: Test CRUD operations

## Invoking the Application
- Log on to my mysql
    - Run SOURCE db/schema.sql to drop and create the database schema
- After models have been created and association methods made,  
run the command: npm run seed  
to populate the database with data
- Run the command: npm run watch  
to initialize the application on the localhost server defined in the connection.js file and use nodemon to restart the server when files are saved
- Test with Insomnia

## Database Setup
<img src="./images/seeds.gif">


## Request Demos

## GET
<img src="./images/GET Requests.gif">  

Get Request Link: https://drive.google.com/file/d/1QLZ7H_wfqYQG6Dse9eXKhHVr55N7ZnHd/view

## POST
<img src="./images/POST Requests.gif">  

Post Requests Link: https://drive.google.com/file/d/1fdkwYW870JSvChujIuofAVocjoG63HcN/view

## PUT
<img src="./images/PUT Requests.gif">  

PUT Requests Link: https://drive.google.com/file/d/1cyRwd8uvmP0padWeUSe74doRLFlwlSEC/view

## DELETE
<img src="./images/DELETE.gif">  

DELETE Requests Link: https://drive.google.com/file/d/1ghbvtsx94ILMOCIfGFzg-gBZBG03E16n/view


