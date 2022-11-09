# Redux Combine Reducers  

## Multiple Reducers Example  

1. Creating multiple reducers enhances the readability of our code, and prevent single errors from stopping all operations in a single reducer.  
2. You combine multiple reducers by using the combine reducers function from redux.  
3. By using the spread operator to create a copy of the state. If don't we will end up returning the same state from before our reducer was run.  

## Redux Docs: using combined Reducers  

1. Redux reducers  
2. It creates a new state with the same keys as the initial state.  
3. We can define initial state by passing it in as an argument to our reducer function.  

## Redux Docs: Combined Reducer Syntax  

1. Each of those reducers will manage a separate part of state. This makes maintaining and reading your code easier, and makes the code more robust against errors.  
2. The combinerReducer function turns objects into a singler reducing function that can be passed to createStore.  
3. Naming them after the slice of state that they manage is a common naming convention.  

## Reflection  

1. I'm interested in learning how we can componetize these parts of state into separate slices.  
