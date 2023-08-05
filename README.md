
# QKart E-commerce Application

QKart is an E-commerce application that offers a variety of products for customers to choose from. During the course of this project, the following features were implemented:

## Features Implemented:

1. **REST APIs**: The complete set of REST APIs was built following best practices.

2. **Layered Approach**: A layered architecture was followed for easy maintenance and scalability.

3. **MongoDB Database**: MongoDB NoSQL database was used for data storage.

4. **Authentication Schemes**: Multiple authentication schemes were implemented to secure API endpoints.

5. **Unit and Integration Tests**: Unit and integration tests were written to test the implementation.

## QKart Layered Architecture

![QKart Layered Architecture](image-link-here)

## Secure API endpoints and implement register/login APIs

In this phase, the following tasks were completed:

- Logic to generate short-lived JWT tokens was implemented.
- Token authentication strategy was set using the Passport library.
- The `GET /v1/users` endpoint was secured using token authentication.
- POST APIs for user registration and login were created.
- Password authentication was implemented to facilitate the register/login flow.

![JWT Token authentication flow for QKart APIs](image-link-here)

## Set up application and implement the first API

In this phase, the initial setup was done, and the first API `GET /v1/users` was implemented to send user data to clients. The following technologies and techniques were used:

- Node.js and Express.js for building the backend server.
- MongoDB and Mongoose ODM for data storage and fetching user data.
- JOI schema for easy validation of client requests.

![Request-response cycle in QKart (Endpoint: /v1/users)](image-link-here)

## Deploy the QKart backend server

In this phase, the QKart backend server was deployed using the following steps:

- A MongoDB instance was set up on MongoDB Atlas cloud, and products data was uploaded to the cloud database.
- The QKart Node.js app was deployed to Heroku for backend hosting.
- The QKart React frontend was deployed to Netlify after configuring it to use the deployed Node.js backend.

## Complete the checkout logic using TDD

The checkout logic was implemented using Test-driven development (TDD) practices. The following steps were taken:

- Jest-based assertions were added to unit tests for checkout requirements provided.
- The checkout logic was implemented in a Test-driven development style.
- Integration tests were used to find and resolve bugs while integrating the checkout logic into the application.

## Implement APIs related to shopping cart

In this phase, the following tasks were completed:

- GET/POST/PUT API endpoints for a user's shopping cart were implemented.
- The `GET /v1/users` endpoint was improved by supporting filtering for user address via query parameters.

These are just some sections that can be included in the markdown file to document the QKart E-commerce application. Feel free to add more details, explanations, and actual links to images as needed. The structure and content can be customized based on the actual implementation and requirements of the project.
