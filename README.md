# data-engineering-zoomcamp-work
This repository comprises data-engineering-zoomcamp experiments, notes and assigments, that I have practiced as part of https://dphi.tech/ Data Engineering Boot camp.

* Kafka Stream processing:
  * Introduction to stream processing
  * Queing Vs Pub-Sub Model
  * Partitions
  * Topics
  * Demo: 
      * 1 Producer, 1 Partition, 1 Consumer
      * 1 producer, 2 Partition, 3 consumer - Observed idle consumer
      * 1 producer, 2 Partition, 3 consumer - Killed existing consumer and verified Idle consumer started processing topics
  * Kafka Schema Registry and Avro serialization:
      * Schema Registry - a seperate independant service for schema validation before sending it to kafka broker
      * Schema validation was complete, Avro serialization was perfomed and topics sent to kafka broker.
      * At consumer check Schema registry and deserialize the schema with any compatible versions.



  * Kafka Stream Processing Notes: https://github.com/thamizhannal/data-engineering-zoomcamp-work/blob/main/week_6_stream_processing/wee6_kafka_schema_avro.pdf


* Reference: 

https://github.com/DataTalksClub/data-engineering-zoomcamp

https://dphi.tech/

