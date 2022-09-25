# Node Ecosystem  

1. Node js is used to run our javascript code with a variety of built in features and uses.  
2. It means that it runs a javascript engine.  
3. To download and run various tools to assist in our modern Javascript applications.  

Node can also be used to run Javascript on servers.  
It is the first real implemention to gain traction.  
Other languages open threads and must wait until an operation is completed before moving on. Subsequent operations are turned into more threads, which can slow the system signifigantly. Node is single-threaded, and when encountering an operation that takes a while can create a callback and continue to execute code.  
The downsides include needing a worker thread for intensive operations, and proper error-handling as a single error can crash the entire server.  
