# Thinking in React  
1. The single responsibility principle is the idea that each component should do one thing. If it is doing too many things at once it should be broken down into smaller compoonents.  
2. A static version is a version of the application that displays without any of the functionality of the final site.  This allows the developer to separate the meanial work from the thinking work.  
3. Breakdown the minmal functionality that your application will need. This will keep you from getting too bogged down in minor features that may not be necassary.  
4. Is it passed from the parents, does it remain unchanged over time, or can you use other props or state to represent it? If not than it shouldn't be state.  
5. You need to identify all the components that will need that state data, and then place it one layer above them.  

## Higher order functions  
1. A function that takes in functions as arguments, or returns them is a higher order function.  
2. It is setting up a new function by keeping one variable empty while n fills in another.  
3. The foreach method allows one to run a block of code through each value in an array. Often times these are methods.  
