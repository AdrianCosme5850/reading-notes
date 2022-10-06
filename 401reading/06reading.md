# Securing Passwords

1. Hashing a password is basically scramling it into something that a program can look at tell if it is the same as the password that was originally put in place.

2. Bcrypt is a algorithim that hashes a password with a certain number of work cycles.  
3. This means that we can make a hash more proccessing expspensive to make it more secure.  

## Basic Auth  

1. Basic authentication is a when a request is made including a username and password.  
2. In the headers field of the request, Authorization and credentials that are base64 encoded are included in the header.
3. They are base64 encoded.

## Authentcation cheat sheet  

1. Authentication process is proving to another machine that you are who you say you are. That means at least providing a username and password that only the client should know.  
2. The error messages should be generic to prevent giving information to the attacker. However, if the data is not critical less generic error messages can be given.  
