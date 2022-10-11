# Socket io Chat Example  

1. In the above app we are creating a real time chat application that allows a couple of users to communicate without needing to refresh in order to get new messages.  
2. To get an intial proof of life we are gettin an intial hello world, and a console log when a user first connects.  
3. .broadcast sends the message to everyone on the socket except the sender.  

## Rooms  

1. A room is apart of socket that you can connect to in the namespace. This way we can send payloads only to users in the room.  
2. socket.join (roomname);
3. socket.emit('disconnect')

# NameSpaces  

1. Allows you to split the logic of your application over a single connection. A single pipeline can be used from client to server, even if the server is split to multiple parts.  
2. Each namespace can use eventHandlers, rooms, and middlewares.  
3. You can create a namespace that only certain users have access to. This can be used to protect privieliged information.  