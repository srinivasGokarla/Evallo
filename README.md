# Evallo Assignment


## Introduction
A mern stack application for managing the authentication of users and upload the files.

## Features
The key features of the application.

- validation and error handling for API requests
- authentication and authorization mechanisms to ensure secure access to the API endpoints
- Upload the files to the specified storage
- Api's for login and regsiter, logout, upload the file,  and get all files


## Deployed link
[link](https://drive.google.com/file/d/19n9gjU_E6xOPYh7kMaeyKqY-_ydj4V96/view?usp=sharing)

## Installation or How to run the app
I created cloud database using MongoDb Atlas. So, if you want to run our code then please read the instructions below :
- Clone our repository https://github.com/srinivasGokarla/Evallo
- Open the code in your VS code, open Backend folder in the terminal by running cd Backend
-Now run npm install or npm i which will install all the required packages of node
- After installation, now run npm run server and  you will see server is listening on 5000 
- Simlutaniously, open a new terminal and run cd frontend by which you get into frontend folder
- Now here, run npm install or npm i which will install all the required packages of react aswell
- After installation, now run npm start and  you will see a new window will be opening in the default browser which is running on port http://localhost:3000
- Open MongoDb compass and url mongodb://localhost:27017/users which will create database collection named users
- Now you see app running, you can click on Register to sign in and after that you will be redirected to Home page.

## API Endpoints
Backend Applications provide a list of API endpoints
- POST /api/register - Register User
- POST /api/login - Login user
- POST /api/logout - Logout the user
- POST /api/upload-image - upload the file or image
- GET /api/get-image - Get all images for the user


## Technology Stack
List and provide a brief overview of the technologies used in the project.

- MongoDB
- Express JS
- React JS
- Node JS
 
 ### Dependencies and packages

#### Backend

- mongoose<br/>
  connecting MongoDB to the Node js server
- jsonwebtoken<br/>
  generate a token for securely transmitting information
- nodemon<br/>
  It monitors your project and automatically restarts when detects any changes.
- cors<br/>
  allowing browser should permit loading resources
- multer<br/>
  allowing to upload the different types of files into the database

#### Frontend
- axios<br/>
  JavaScript library to make HTTP requests or fetching data
- react-router-dom<br/>
  implementaion of dynamic routing
- multer<br/>
  using to upload the file and show the files on browser
  
  
#### Cloud Deployment

- Render
used Render for deploying the MongoDB (database), node js (Backend).
- vercel 
used vercel for deploying reactjs(frontend)

