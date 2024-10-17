# REST API Projects

This repository contains REST API project created using **Postman**. Project demonstrate the use of core HTTP methods such as **GET**, **POST**, **PUT**, **PATCH**, and **DELETE**. The project include a collection of requests, an environment file for dynamic variables, and a runner collection for executing tests in a specified order.

## Project Files

### 1. REST API Postman Collection
- **`REST API.postman_collection.json`**: A collection of HTTP requests, showcasing various API operations (GET, POST, PUT, PATCH, DELETE).
  
### 2. REST API Runner Collection
- **`REST API Runner.postman_collection.json`**: A runner collection that executes the API requests in a specific sequence. This can be used for running tests in a predefined order.

### 3. REST API Environment
- **`REST API.postman_environment.json`**: Environment file containing variables that are reused across requests in the collection (e.g., `baseURI`, `objectID`).

## Overview

Each project supports the following functionalities:
- **GET**: Retrieve data from the API.
- **POST**: Create new data in the API.
- **PUT**: Update existing data.
- **PATCH**: Partially update existing data.
- **DELETE**: Remove data.

### Key Features
- **Manual API Execution**: All API requests are run manually using Postman.
- **Environment Variables**: The use of dynamic environment variables (e.g., `objectID`) for flexible testing.
- **Collection Runner**: Execute the API requests in a pre-defined order through the Postman Runner.

## How to Use

1. Clone or download the repository.
2. Open Postman.
3. Import the following files into Postman:
   - `REST API.postman_collection.json`
   - `REST API Runner.postman_collection.json`
   - `REST API.postman_environment.json`
4. Set the imported environment as active.
5. You can manually run individual requests or use the Postman Collection Runner to execute the tests in sequence.

## About the Project

This project is designed to showcase basic REST API operations and test them manually through Postman. They do not include automation but provide a foundation for understanding API interactions and testing.


