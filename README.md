# kafka-springboot-demo
## Point to Point messaging system
> * In point to point messaging system message are persisted in a queue
> * One or more consumber can consume the message in a queue but a particular message can be consume by maximum a of one consumer only.
> * Onces a consumer read a mesage , that particular message got disappear from the queue
> * **Order processing** is the best example of this system where each order can be proced by one order processor but multiple order processor can work as well.
![image](https://github.com/user-attachments/assets/ca1ca897-1b8b-454c-8832-f6965c70c6f0)

## Publish Subscribe messaging system
> * In publish subscribe system message are persist into a topic.
> * In this system consumer ca subscribe multiple topics and can consume all message in that topics
![image](https://github.com/user-attachments/assets/df2b6afd-f875-481e-a2e1-fadde850e118)

## What is Kafka 
> * Kafka is a distributed publish subscribe messaging system and roubst queue that can handle high volumn of data.
> * Kafka is suitable for both online and offline
> * Kafka message are persisted on the disk and replicated within cluster to prevent data loss.
> * Kafka is build on top of **Zookeeper** synchronization service

### What are the Benifits of Kafka 
> * **Reliability** :- Kafka is distributed partitioned replicated and fault tolerance.
> * **Scalibility** :- Kafka scales easly without any downtime
> * **Durabilities** :- Kafka uses distributed commit log  which meanssage persist on disk as fast as posible.
> * **Performance** :- Kafka is high throwput for both publish ad subscribe message
> * Kafka is very fast and guranty zero downtime.### What are the Benifits of Kafka

### What are the Use case of Kafka 
> * **Metrics:-**
> * **Log aggregation solution:-** Kafka can be user into across organization to collect the log from multiple services and make it available in a standered format to multiple consumer.
> * **Stream Processing:-**
![image](https://github.com/user-attachments/assets/22fe5548-4b2d-4e9a-be2f-992ee09bf558)
