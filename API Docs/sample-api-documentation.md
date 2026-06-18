#User Registration API
## Overview
This API allows users to create a new account.
## Endpoint
POST/users/register
|name|string|Yes|
|email|string|Yes|
|password|string|Yes|
## Sample Request
{"name":"john Doe"
"email":john@example.com"
password":password123"}
## Successful Response
{"message":User created successfully
"userId":123}
## Error Response
{"error:Email already exists"}
## Status Codes
|Code|Meaning|
|201|User created|
|400|Invalid request|
|409|Email already exists|
## Notes
-Email addresses must be unique
-Passwords should contain at least 8 characters .
-Users must verify their email after registration