This project uses JWT to secure the REST endpoints.

The Following are the REST end points available.

/token - Generates the JWT token based on the JSON sent. Its a POST method which expects the JSON: { "username": "name", "id": 123, "role": "admin"}
/rest/hello - Requires a JWT Token with Header key - "Authorisation" and value - "Token <JWT_Token>"
