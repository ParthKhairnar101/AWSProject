# Task List CRUD Application

A simple task list (to-do list) CRUD application built using React.js for the front end and Express for the backend. This project is deployed using AWS services like DynamoDB, AWS Amplify, and AWS Lambda. It's part of an AWS Solutions Architect class project.

## Features

- Create, read, update, and delete tasks.
- Responsive UI built with Material-UI components and icons.
- State management using classnames.
- Backend server application using Express.
- Deployed using AWS services.

## Tech Stack

**Frontend:**
- React.js (created with `npx create-react-app`)
- Material-UI components and icons
- Axios for HTTP requests
- classnames for conditionally joining class names

**Backend:**
- Express.js
- Nodemon for development
- CORS for cross-origin requests
- Serverless HTTP for AWS Lambda integration
- AWS SDK for DynamoDB: `@aws-sdk/client-dynamodb`, `@aws-sdk/lib-dynamodb`

**AWS Services:**
- DynamoDB
- AWS Amplify
- AWS Lambda

## Installation

## Clone the repository:

```bash
git clone https://github.com/ParthKhairnar101/AWSProject.git
```

## Navigate to the project directory:

```bash
cd AWSProject
```

## Install dependencies for both frontend and backend:

### Frontend

```bash
cd ui
npm install
```

### Backend

```bash
cd ../api
npm install
```

## Running the Application

### Frontend

```bash
cd ui
npm start
```

- Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Backend

```bash
cd api
npm run dev
```

## Deployment

This project is deployed using AWS services:

- **DynamoDB** for the database
- **AWS Amplify** for hosting the frontend
- **AWS Lambda** for backend functions

Follow the instructions provided in the AWS documentation for each service to set up the deployment.

## License

This project is licensed under the MIT License.
