# Intro to JWT  

1. JSON Web Tokens are a signed json object that a machine can use to prove they are a verified user.
2. JWTs can be used to authorize users, or to send information. The information is signed with a public private key value that allows you to be sure it came from the right people.  
3. Claims are expected in the payload part of the JWT.

## JWT explained

1. Because if you changed the payload and tried to send it, the digital signature would be different, and the machine would notice.  
2. Both users must know the hash and the secret.  
3. They are used by a hash to scramble the password with the secret as the key. Without the key to unscramble, a malicious user can't unscramble it.  

## JWT explained 2  

1. We use JWT because it can be used to authenticate a user, and exchange information.  
2. Because they are compact and self-contained, we can avoid querying the database more than once, and they have fast transmission.  
3. A JWT signature is a combination of the base 64 header and base64 payload with the secret.  
