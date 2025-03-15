
# Serverless GraphQL Backend

This repository contains the backend for a serverless GraphQL API service built with Node.js and AWS services. It leverages AWS Lambda, API Gateway, and DynamoDB to efficiently handle GraphQL queries and mutations.

## Overview

The serverless GraphQL backend processes incoming GraphQL requests, executes the necessary logic, and returns data, effectively acting as the core of the API.

## Technologies Used

- **Node.js:** JavaScript runtime environment.
- **AWS Lambda:** Serverless compute service.
- **API Gateway:** Manage API endpoints.
- **DynamoDB:** NoSQL database service.
- **Apollo Server:** GraphQL server implementation.

## Getting Started

Follow these steps to set up and run the project:

### 1. Install Dependencies
Run the following command in the project root:

```bash
npm install
```

### 2. Start the Server
Launch the Apollo Server by running:

```bash
npm start
```

This command will start your Apollo Server as defined in `server.ts`.

## Additional Configuration

Before you run the project, ensure that your AWS credentials are correctly configured:

- **Configure AWS Credentials:**  
  Run the following command and provide your AWS Access Key, Secret Access Key, and region when prompted:
  ```bash
  aws configure