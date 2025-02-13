 User Management API

 Project Overview
The User Management API is designed to manage user records for TechHive Solutions. It provides endpoints for creating, reading, updating, and deleting (CRUD) user information. The API is built with ASP.NET Core and includes middleware for logging, error handling, and token-based authentication.

 Features
- CRUD Operations: 
  - GET: Retrieve a list of users or a specific user by ID.
  - POST: Add a new user.
  - PUT: Update an existing user's details.
  - DELETE: Remove a user by ID.
- Middleware:
  - Logging: Logs HTTP requests and responses.
  - Error Handling: Catches unhandled exceptions and returns consistent error responses in JSON format.
  - Authentication: Validates tokens from incoming requests and allows access only to users with valid tokens.
- Validation:
  - Ensures only valid user data is processed, with attributes for required fields, email format, and phone number format.

 Getting Started

 Prerequisites
- .NET SDK
- Visual Studio Code or any preferred code editor
- Git
- Postman (optional, for testing)

 Installation
1. Clone the Repository:
   
   ```bash
   
   git clone https://github.com/Baffoe6/UserManagementAPI.git
   cd UserManagementAPI
