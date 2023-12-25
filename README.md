# Photos API

## Auth Endpoint

> Register User
> POST http://localhost:3001/api/v1/auth/register

* Create New User
* Request Body
 ```
 {
    "username": "danuputra",
    "email": "danuputra",
    "password": "danuputra"
 }
 ```
* Response Body :
     * 201 Created
       ```
       {
         "message": "User registered successfully",
         "success": true
       }
       ```
