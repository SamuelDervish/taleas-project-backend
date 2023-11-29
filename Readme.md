# Node.js Backend for JS Web Application

Welcome to the Node.js backend of our JavaScript web application! This backend is built using AWS CDK to manage infrastructure components. The application includes user authentication, controllers for handling requests, GitHub checks for continuous integration, and automatic deployment from GitHub. Additionally, content moderation and image checking using AWS Rekognition have been implemented.

## Features

- RESTful API with controllers for handling various requests.
- User authentication using AWS Cognito User Pool.
- GitHub checks for continuous integration.
- Automatic deployment from GitHub using AWS CDK.
- Content moderation for user-generated content.
- Image checking using AWS Rekognition for identifying inappropriate images.

## Technologies Used

- Node.js
- Express.js
- AWS CDK
- AWS Cognito
- AWS Rekognition

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/SamuelDervish/taleas-project-backend.git
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up AWS CDK and deploy the infrastructure.

4. Configure AWS Cognito User Pool and GitHub Actions for continuous integration.

5. Start the backend server:

    ```bash
    npm start
    ```

6. Start using the backend API in your JavaScript web application.

## Controllers

The backend includes controllers for handling the following operations:

- User registration and authentication.
- Content moderation and filtering.
- Image checking using AWS Rekognition.

## Continuous Integration

GitHub Actions are set up to perform checks on every push to the repository, ensuring code quality and passing tests before deployment.

## Automatic Deployment

The application is automatically deployed from GitHub to the AWS infrastructure using AWS CDK.

## Content Moderation and Image Checking

Content moderation is applied to user-generated content, and image checking is performed using AWS Rekognition to identify and filter out inappropriate images.

## Contributing

Feel free to contribute by submitting pull requests or opening issues.


Thank you for contributing to a secure and robust Node.js backend!
