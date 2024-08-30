# Create an APIS using flask, request and jsonify

A simple Flask application that provides an API endpoint to fetch user details based on a user ID. It supports an optional query parameter to include additional information in the response.

## Feature
## Endpoints
### 1. **GET /get-user/<user_id>**

- **GET /get-user/<user_id>**: Retrieves user details for a given user ID.
  - **Path Parameter**:
    - `user_id`: The unique identifier for the user.
  - **Query Parameter** (optional):
    - `extra`: Additional information to include in the response.

## Prerequisites

- Python 3.6 or higher
- Flask

### Running the Application
python main.py
The server will start at http://127.0.0.1:5000 by default. You can access the API endpoint as follows:

Get User Details:

URL: http://127.0.0.1:5000/get-user/<user_id>
Method: GET
Query Parameter: extra

*Request*
"http://127.0.0.1:5000/get-user/123?extra=hello"

### Json Object Response
{
    "user_id": "123",
    "name": "Ruchit Soni",
    "email": "ruchitsoni1898@gmail.com",
    "extra": "\"hello\"",
}

#### POST /create-user
Creates a new user with the provided JSON data.
http://127.0.0.1:5000/create-user




