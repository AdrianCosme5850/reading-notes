# Lecture 6  

## Authentication and Authorization  

Authentication is proving you are who you say you are.  
Username and password are the least secure, but also simplest.  
Authorization gives permissions on what a user can access.  
Encryption is a way to hide things from prying eyes.  
Encoding is taking information and standardizing it. This is so that other systems can interpret that data.  
On the intial POST request we send the username and password in the JSON body.  
On subsequent sign-in requests, send the username and password encoded in the header.  
