ANTARMAN

Antarman is a Full Stack Chatting App.
Uses Socket.io for real time communication and stores user details in encrypted format in Mongo DB Database.


**Client:** React JS

**Server:** Node JS, Express JS

**Database:** Mongo DB

## Run Locally


1. Install mongodb with MongoDB Compass
2. download above file unzip it
3. open in VS code
4. open terminal
5. split terminal into two
6. First Terminal
     npm install
     cd frontend
     npm install
     npm start
7.open mongoDB in chrome sign in
    databas-connect-compass-i have mongodb-copy connection string
   --Go to compass-new connection-add copied URL- enter you own password
8. no open the vs code and create .env file -copy the code given below
    PORT = 5000
    MONGO_URI = (above copied URL with your password)?retryWrites=true&w=majority
    JWT_SECRET = your name
9. Second Terminal
     cd backend
     npm install
     npm start

   You are good to go.....

   
