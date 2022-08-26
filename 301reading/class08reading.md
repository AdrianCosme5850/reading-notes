# API's  

## API design best practices.  

1. REST stands for Representational State Transfer.  
2. REST is an architecural style for building distributed systems based on hypermedia.  
3. An identifier of a resource is a URL that is unique to that resource.
https://adventure-works.com/orders/1 is an example.  
4. The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE.  
5. A good URI is intuitive and not overly complex. It shouldn't go more than three layers deep, as this can become cumbersome and hard to implement.  
6. /customers/orders/5  
7. A chatty API is one that has too many requests. Try to keep the number of requests low to keep the burden on the API light.  
8.  status code 200  
9. status code 404  
10. status code 201  
11. status code 201