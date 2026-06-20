# API Reference

## Base URL

https://api.example.com/v1

## Authentication

All API requests require an API key.

Example:

Authorization: Bearer YOUR_API_KEY

## Get User

### Endpoint

GET /users/{id}

### Request

GET /users/123

### Response

```json
{
  "id": 123,
  "name": "John Doe",
  "email": "john@example.com"
}
```

### Status Codes

| Code | Description    |
| ---- | -------------- |
| 200  | Success        |
| 404  | User not found |
| 500  | Server error   |