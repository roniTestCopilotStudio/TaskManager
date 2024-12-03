# API Authentication

To authenticate with the TaskMaster API, use the following method.

## JWT Authentication

TaskMaster uses JSON Web Tokens (JWT) for authentication. Include the token in the `Authorization` header of your requests.

```http
Authorization: Bearer your_jwt_token
```

## Obtaining a Token
To obtain a token, send a POST request to the /auth/login endpoint with your credentials.

```
POST /auth/login
{
  "username": "your_username",
  "password": "your_password"
}
```

