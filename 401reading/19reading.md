# AWS: Events  

## AWS SQS vs SNS  

1. SQS is a queuing system, while SNS is a publish-subscribe service. SNS allows you to send push notifications to phones and a large number of recipients. SQS stores messages until it is pinged by the receiver.  
2. SNS can be used for multiple subscribers, and can process a large amount of messages. SQS is if you need a simple one to one communication queue.  

## AWS SNS and SQS  

1. Users subscribe to a topic, and then a message is sent to a topic which is then sent out to all individuals subscribed to the topic.  
2. They are published to the topic with relevant information, and then sent to all subscribed users.  

## SQS and SNS Basic  

A large scale application can store payloads in the queue without the fear of needing to request again if operations fail.  
