# JwtAuthenticationExample
Simple example using JWT Token authentication in .NET 6

# Testing
The project includes a Swagger documentation. Use the basic url for Swagger (localhost:port/swagger/index.html)

# Login
Login endpoint validates the username, password and the JWT token generated after the register. 

If you try to login without register the user first you'll receive message "400 User Not Found"

If you register your user first the token will be genetated and you are able to login with this user. If you try to login with another user or password it will be unauthorized.

