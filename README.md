# Spring-Integration-Kafka
Sample project for using spring integration with Kafka. Its based on spring boot.

## Problem Statement
- Vanilla producer-consumer (Done)
- Write a producer which sends continous 1 lakh message a Topic with 20 Partition and Increase the consumers gradually from 1 to 20 after fixed interval. Verify that no message is lost due to partition reallignment.
- Do we need synchronous message publishing or can live with asynchronous send. 


## Steps
- [Start Kafka](doc/Kafka.md)
- Start application as java application with Application.java as main class. 

## Licence 
NA


## References
    - https://www.tutorialspoint.com/apache_kafka/index.htm
    - https://www.youtube.com/playlist?list=PLkz1SCf5iB4enAR00Z46JwY9GGkaS2NON
    
