# OAuth
  
1. OAuth is a third party authentication software.  
2. The user sends a request for access to OAuth, OAuth sends a token, the user uses the token to request the server, the server confirms with oauth that its a good token.  
3. OAuth is used for authorization not authentication. Once the user is authenticated oauth securely authorizes.  
4. OpenID is for Authentication.  

# Authorization and authentication flow  

1. Authorization is for proving a user is who they say they are. Authentication is for machines.  
2. Authorization code flow is the exchange of an authorization code for a token which is used to make a request of the server.  
3. Mobile and single page applications pose special challenges for security and require a proof key for security.  
4. It is a more streamilined form of authorization, however it is no longer considered best practice.  
5. The system authorize the machine rather the the client after authentication is complete.  
6. The user follows a link in order to authenticate the device. THis provides a better user expericnce.  
7. It is for highly trusted application, and should only be used if or flows are not available.  

