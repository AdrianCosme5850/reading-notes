# Advanced State with Reducers  

## useReduce Hook  

1. The useReduce hook can be used as an alternative to the useState hook.  
2. It is preferable to useState hook when you have complex state logic or when the state of an object depends on the state of a previous one.  
3. You can either pass in state as a second argument, or pass an init function so that you can determine the intial state outside of the reducer hook.  

## Ultimate guide to useReducer  

1. It expects to receive a reducer function and an intial state.  
2. It returns an array that holds that state, and a function to later invoke that state.  
3. The dispatcher function sends an update to state to be processed through the reducer.  

## Reflection  

1. My learning goals are to gather more information on the dispatch function, as I don't feel confident in implementing it in my code.  
