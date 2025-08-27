---
applyTo: "assignments/**/*.md"
---

# Build REST APIs with FastAPI ✨

## Objective
Build a RESTful API using the FastAPI framework. Students will learn how to create endpoints, process requests, and return responses in JSON format.

## Tasks

### Task 1: Setup FastAPI Project
**Description:**
Initialize a new FastAPI project and create a basic endpoint.

**Requirements:**
- Create a new FastAPI application.
- Implement a GET endpoint at `/` that returns a simple JSON response.

**Example Input/Output:**
```
GET /
Response: {"Hello": "World"}
```

### Task 2: Enhance API Functionality
**Description:**
Add additional endpoints to handle different HTTP methods (POST, PUT, DELETE).

**Requirements:**
- Create endpoints for POST, PUT, and DELETE operations.
- Validate incoming request data.
- Return appropriate JSON responses.

**Example Input/Output:**
```
POST /items
Input: {"name": "Item"}
Response: {"name": "Item", "id": 1}
```

## Resources
- Refer to the starter code in `starter-code.py`.
- FastAPI documentation: https://fastapi.tiangolo.com/
