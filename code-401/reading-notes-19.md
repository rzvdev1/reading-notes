# AWS: Events

## AWS SQS vs SNS

Amazon SQS (Simple Queue Service) is a distributed queue system and Amazon SNS(Simple Notification Service) is a distributed publish/subscribe system.

What are some use cases for both SNS and SQS?
The case to use SNS is when you want to send a message to a bunch of subscribers of a topic. The case to use SQS is when you want to have a queue of messages to be processed asynchronously.

## AWS SNS and SQS

Describe how to use SQS and SNS in a “fanout” pattern.

To use SQS and SNS in a fanout pattern, you would create a topic in SNS and then create a queue in SQS. Then you would subscribe the queue to the topic. Then you would publish a message to the topic and it would be sent to the queue.

Explain how “push notifications” work, using SNS.

The push notification is sent to the SNS topic and then the topic sends the message to the SQS queue. The queue then sends the message to the subscriber. The subscriber can be an email address, a phone number, or an HTTP endpoint.

## SQS and SNS Basics

How might a large scale, distributed application make use of a Queue system like SQS?

A large scale, distributed application might use SQS to process messages asynchronously. This would allow the application to scale up and down as needed. It would also allow the application to process messages in the order they were received. In the case of a failure, the message would be returned to the queue to be processed again. This would allow the application to be fault tolerant.

### Resources I use

Difference between SQS and SNS[^1], SNS vs SQS Comparison[^2], and Decouple and Scale Applications Using Amazon SQS and Amazon SNS[^3]

[^1]: [AWS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)
[^2]: [YouTube](https://www.youtube.com/watch?v=mXk0MNjlO7A)
[^3]: [YouTube](https://www.youtube.com/watch?v=UesxWuZMZqI)
