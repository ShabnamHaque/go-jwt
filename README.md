# Golang_JWT_Project
Backend with authentication and validation that maintains and addresses a MongoDB Database
<br><br>

1. We will implement hashing of user passwords.<br>

2. Maintain access points (User or Admin) - special access privilege using tokens. <br>

3. Last updated time, created-at time, token, refresh token,userId etc. <br>

4. Special access of all available users to the Admin. <br>

5. Only the user themselves or the admin can access Logging in to access the user data. <br>

6. Password Encryption. <br>
```
C:.
│   .env
│   go.mod
│   go.sum
│   main.go
│   
├───controllers
│       userController.go
│       
├───database
│       databaseConnection.go
│       
├───helpers
│       AuthHelper.go
│       TokenHelper.go
│
├───middleware
│       authMiddleware.go
│
├───models
│       userModel.go
│
└───routes
        authRouter.go
        userRouter.go
```
        
.env file of the format
```
PORT=[..]
MONGODB_URL=[...]
SECRET_KEY="xyz"
```
