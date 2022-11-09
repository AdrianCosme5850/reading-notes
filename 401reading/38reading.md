# Redux - async actions  

## Async actions  

1. When we need to use a side effect redux by default does not allow it. Using middleware is the solution to that problem.  
2. The event is dispatched to the reducer, however before it reaches the reducer it is passed through the middleware we have setup. it is then passed on by the next function.  
3. We either create or use the built in thunk middleware to resolve the promise and then dispatch it.  

## Thunk middleware  

1. Our reducers can no take in promises, and therefore require something to resolve them before the payload can be passed to the reducer.  
2. It allows you to write action creators that return a function rather than an action.  
3. It will dispatch again once finished.  

## reflection  

1. I want to learn how to manage as much as possible in Redux to make my components as reusable as possible.  
