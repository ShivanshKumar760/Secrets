# Secrets Website

## Description

The Secrets Website is a web application that allows users to share their secrets anonymously. Users can register, log in, and post secrets without revealing their identities. The application ensures user authentication and session management using Express, Node.js, MongoDB, and session handling. The project is deployed on Render.





## Feature

- User Registration and Login
- Anonymous Secret Sharing
- Authentication and Session Management
- Secure and Scalable Backend
- Deployed on Render for seamless accessibility
## Pre-requisites
Make sure you have the following installed:

- Node.js
- MongoDB
- Express.js
- Mongoose
- Passport.js
- EJS
## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/secrets-website.git
   cd secrets-website
   ```


2. install dependencies:
     ```sh
    npm install

3.Create a .env file and add the following environment variables:
    ```
    PORT=3000
    MONGO_URI=your_mongodb_connection_string
    SESSION_SECRET=your_session_secret
    ```

4.Start the MongoDB server:
    ```
    mongod
    ```
5.Start the application:
    ```npm start```

6.Open your browser and navigate to:
    ```http://localhost:3000```



## Usage
- Register a new account or log in if you already have an account.

- Share your secrets anonymously on the platform.

- View the secrets shared by other users
## Deployment
The application is deployed on Render. Follow these steps to deploy: 

    1. Create an account on Render and link your GitHub repository. 
    2. Set up a new web service on Render and configure the environment variables as specified in the .env file. 
    3. Deploy the application from the Render dashboard.
## Tech Stack
### Backend
![nodejs](https://github.com/ShivanshKumar760/Secrets/blob/master/mdfile-assets/nodejs.png)
![express](https://github.com/ShivanshKumar760/Secrets/blob/master/mdfile-assets/express.png)
![MongoDB](https://github.com/ShivanshKumar760/Secrets/blob/master/mdfile-assets/mongodb.png)
![mongoose](https://github.com/ShivanshKumar760/Secrets/blob/master/mdfile-assets/mongoose.png)
![Passport](https://github.com/ShivanshKumar760/Secrets/blob/master/mdfile-assets/passport.png)
- Node.js: JavaScript runtime environment.

- Express.js: Web application framework for Node.js.

- MongoDB: NoSQL database for storing user data and secrets.

- mongoose: ODM for MongoDB to manage data relationships and validation.

- express-session: Middleware for managing user sessions.

- connect-mongo: MongoDB session store for Express.

- Passport.js :For authentication 

### Frontend
![ejs](https://www.step2gen.com/nodejs-development-company-india)
![css](https://www.step2gen.com/nodejs-development-company-india)
![Bootstrap](https://www.step2gen.com/nodejs-development-company-india)
- EJS: Embedded JavaScript templates for server-side rendering.

- CSS: Styling the application
