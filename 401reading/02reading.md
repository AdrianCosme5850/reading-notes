# Express, NPM, TDD, CI/CD  

## NodeJS and Express  

1. Middleware is software that operates between the request and the actual endpoint function. A good example is a validator that checks to see if the request from the server has the right information, and if not it sends an error.  
2. Express is the most popular Node web framework.  
3. Unopinionated means the software doesn't have a right way to do something. The developer writes the code to solve the problem however they want.  
4. A module is code in a file that can be imported to another. This is useful to keep code clean and legible.

## NPM  

1. I am currently running 8.19.1 on my machine.  
2. npm i jshint

## TDD  

1. Tests are important because it allows us to simply our goals into a number of achievable tests. It will also help us identify if something has broken because of changes we make later on down the line.  
2. Expected benefits of testing include reduced defect rates, reduced effort in achieving final phase goals, and improved quality of overall code.  
3. Two common pitfalls are forgetting to run tests enough and writing tests for insignifigant things. Two team pitfalls are partial adoption by the team, and poor maintence of the testing suite.  

## CI/CD  

1. Continous integration ensures everyones code can be integrated properly, catch bugs, and reduce merge conflicts.  
2. Continous delivery is when you develope in such a way that it could be realsed at any time. Deployment is deploying newly developed features provided by continous delivery.  
3. Github can test the code being put into the main branch and see if the changes are able to be merged, and pass tests.  
