# Task 1 [Week-1]: Quora-like App Backend

**Task Title**: Creating a Manual HTTP Server and Basic APIs with Logging

## Problem Statement
Build a simplified version of a question-answer platform similar to Quora using Node.js. In this task, you will create a manual HTTP server (without using Express.js), implement basic CRUD (Create, Read, Update, Delete) APIs for managing questions and answers, and integrate logging with various levels to improve monitoring and debugging.

## Requirements

### 1. Manual HTTP Server
- Utilize the built-in `http` module from Node.js to create an HTTP server.
- Set up routes to handle different endpoints for CRUD operations on questions and answers.

### 2. Basic API Endpoints
- Implement the following API endpoints for questions:
  - `POST /questions`: Create a new question.
  - `GET /questions`: Retrieve a list of all questions.
  - `GET /questions/:id`: Retrieve a specific question by its ID.
  - `PUT /questions/:id`: Update a specific question by its ID.
  - `DELETE /questions/:id`: Delete a specific question by its ID.
- Implement the following API endpoints for answers:
  - `POST /answers`: Create a new answer.
  - `GET /answers`: Retrieve a list of all answers.
  - `GET /answers/:id`: Retrieve a specific answer by its ID.
  - `PUT /answers/:id`: Update a specific answer by its ID.
  - `DELETE /answers/:id`: Delete a specific answer by its ID.

### 3. Data Storage
- Use file system operations (read and write) to store question and answer data in JSON files (`questions.json` and `answers.json`).
- Ensure data integrity by properly handling concurrent read/write operations.

### 4. Logging with Different Levels
- Integrate a logging library such as `winston` to provide logging functionality with different levels (e.g., info, debug, error).
- Log relevant information, including:
  - HTTP requests (e.g., method, URL, status code)
  - API endpoint hits
  - Error messages and stack traces
  - Application events (e.g., server start, file operations)

### 5. Error Handling
- Implement basic error handling to catch and respond to errors gracefully.
- Ensure proper error messages are logged with appropriate log levels.

### 6. Testing
- Use tools like cURL or Postman to test the API endpoints and verify they work as expected.
- Ensure logs are generated with different levels and contain relevant information.

## Submission Guidelines
- **Source Code**:
  - Submit the source code of your manual HTTP server, API implementations, and logging setup.
- **Documentation**:
  - Provide instructions on how to run the server and interact with the APIs.
  - Include detailed documentation outlining:
    - The API endpoints
    - Request and response formats
    - Logging configuration
    - Any additional features or considerations

## Learning Objectives
- Gain experience in setting up manual HTTP servers using Node.js.
- Implement basic APIs for a question-answer platform.
- Integrate logging to enhance monitoring and debugging capabilities.
- Handle errors gracefully and ensure robust application behavior.
- Test API endpoints to ensure correctness and reliability.
