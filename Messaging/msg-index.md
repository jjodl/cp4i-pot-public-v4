## Introduction to Messaging and Events
So when would you use traditional messaging capabilities such as IBM MQ compared to the newer event streaming technologies such as Kafka as implemented in IBM Event Streams.
In this section we have labs on both the MQ and Event experience.  

[Return to main lab section](../index.md#lab-section)

## Lab PreReq
Before starting the **Kafka Event Steam** or the **MQ labs** make sure that you complete the following prereq setup. 

|  Subject                            | Description                                            |                                                               
|-----------------------------|------------------------------------------------------------------------------------------------------------|
| [Create Connection to shared Kafka cluster.](Msg-Pre-lab/kafkasetup/kafka-connect.md)      | Before starting the **Kafka Event Streams** or the **Event Endpoint Experience labs** make sure that you have completed the **kafka cluster connection setup.**  Steps to create Kafka connection and save credentials and certs for all Kafka labs.
|-----------------------------|
[MQ Environment setup](Msg-Pre-lab/mqsetup/mq_setup_steps.md) | MQ Environment Setup - download MQ lab artifacts
|--------------------------------|-----------------------------------------------------------------|

## Lab Abstracts
### Event Streams
Event Streams is an full-scale event streaming platform that incorporates kafka with IBM created technology for easier administration, capable of not only publish-and-subscribe, but also the storage and processing of data within the stream. 
Event Streams is an kafka event-streaming platform that helps you build smart apps that can react to events as they happen.

|  Subject                       | Description                                                                                         |                                                               
|--------------------------------|-----------------------------------------------------------------|
| [Kafka Experience](Kafka/index.md)       | We have serval labs that will give you hands on using varies capabilities of Kafka Event Streams                      | 
|--------------------------------|-----------------------------------------------------------------|

### MQ
You can use IBM MQ to enable applications to communicate at different times and in many diverse computing environments.
*   **Point-to-point messaging:**
   Senders produce messages to a queue, and receivers asynchronously consume messages from that queue. MQ provides a 
   ‘safe place’ for messages between applications. So, applications or servers being down means that message aren’t lost.

 *  **Request/Response messaging:**
Request/response messaging, or ‘conversational messaging’ is very 
similar to point-to-point, but in this case we need/want a response 
to our message. To make things run more smoothly, many 
customers create special temporary queues for response messages 
– so the sending application can send the message, get on with 
other tasks and monitor the temporary queue for a response.

|  Subject                       | Description                                                                                         |                                                               
|--------------------------------|-----------------------------------------------------------------|
| [MQ Experience](MQ/index.md) | We have serval labs that will give you hands on using varies capabilities of MQ
|--------------------------------|-----------------------------------------------------------------|

[Return to main lab section](../index.md#lab-section)