# API integration  

## Review API Server Build  

1.  A path parameter determines where to look for the information, while the query parameter determines the different options for that path.  
2. http://our-site.com/v3/stuff?id=things  
3. The interface makes a request to the server that locates information in a database. Once it is found it sends that information back to the front-end.  

## Review Auth Server Build  

1. There is a basic auth middleware that takes in the two strings given and then compares it to the strings kept in storage. The bearer auth takes the JWT token and verifies it against the secret stored in the server. Once they are verified by one of the methods they can access the information in the server.  
2. The browser intiates the handshake, and once granted permission it will send a get request to your server. The auth middleware then finishes the handshake.  
3. Basically you create a set of roles that users are assigned. This gives them access to certain parts of your application based on the necessary functions of their job.  

## Reflection  

1. I am interested in learning more about cookies in our browsers, and how they are integrated.  
