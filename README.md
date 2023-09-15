
Ecommerce web app

## Overview

This project is a web application built using the MERN (MongoDB, Express.js, React, Node.js) stack. It incorporates JWT (JSON Web Token) authentication for user authentication and braintree payment gateway integration for processing payments. The application has also been deployed on https://blushing-elk-vest.cyclic.cloud/.

 (their is a client folder which consists all the frontend part code. and all the backend code is in the root directory itself.)
 

## Technology Stack

- **Frontend**: React,JavaScript,Antd,Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Payment Gateway**: braintree

## Features

- User registration and authentication using JWT.
- Seamless integration of the BrainTree payment gateway for processing payments.
- Their is a admin section where user can manage all the users details.
- -Mongodb No Sql database used
- Filter on price amd category


## Setup

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/your-project.git
   ```

2. Install dependencies for both the frontend and backend:

   ```shell
   cd your-project
   cd client && npm install
   cd ../server && npm install
   ```

3. Configure environment variables:

   - Create a `.env` file in the `server` directory and add the necessary environment variables (e.g., MongoDB URI, JWT secret, Stripe API keys).

4. Run the application:

   - Start the backend server:

     ```shell
     cd server && npm start
     ```

   - Start the frontend:

     ```shell
     cd client && npm start
     ```

5. The application should now be running on https://blushing-elk-vest.cyclic.cloud/.

## JWT Authentication

This project uses JSON Web Tokens (JWT) for user authentication. When a user registers or logs in, a JWT token is generated and sent to the client. This token is then included in the headers of authenticated requests to the server. The server verifies the token to authenticate the user.

## BrainTree Payment Gateway

We have integrated the Braintree payment gateway to facilitate secure and seamless payment processing.

## Deployment

This project has been deployed on [Cyclic](https://blushing-elk-vest.cyclic.cloud/).

