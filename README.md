# [Applying the Lambda Architecture with Spark, Kafka, and Cassandra](https://www.pluralsight.com/courses/spark-kafka-cassandra-applying-lambda-architecture)

<!-- MarkdownTOC -->

- [Intro](#intro)
	- [Having problems? See troubleshooting](#having-problems-see-troubleshooting)
	- [Fast track to Scala](#fast-track-to-scala)
- [Batch layer with Apache Spark](#batch-layer-with-apache-spark)
	- [Fundamentals of batch layer](#fundamentals-of-batch-layer)
	- [Aggregations in Spark](#aggregations-in-spark)
	- [Introduction to Spark](#introduction-to-spark)
	- [Spark Components and Scheduling](#spark-components-and-scheduling)
- [Speed layer with Spark Streaming](#speed-layer-with-spark-streaming)
	- [Spark Streaming fundamentals](#spark-streaming-fundamentals)
	- [Log Producer - Stream Data to Files](#log-producer---stream-data-to-files)
	- [Streaming Aggregations](#streaming-aggregations)
	- [Cleaner Code](#cleaner-code)
	- [Advanced Streaming Operations](#advanced-streaming-operations)
		- [Checkpointing](#checkpointing)
		- [Window Operations](#window-operations)
		- [Stateful Transformations](#stateful-transformations)
		- [Streaming Cardinality Estimation](#streaming-cardinality-estimation)
		- [Algebird Library](#algebird-library)
	- [Streaming Aggregations with Apache Zeppelin](#streaming-aggregations-with-apache-zeppelin)
- [Streaming Ingest with Kafka and Spark Streaming](#streaming-ingest-with-kafka-and-spark-streaming)
	- [Kafka](#kafka)
		- [Kafka Producer](#kafka-producer)
		- [Spark Streaming Integration with Kafka](#spark-streaming-integration-with-kafka)
		- [Integrate Batch and Streaming](#integrate-batch-and-streaming)
	- [Persist with Cassandra](#persist-with-cassandra)
		- [Apache Cassandra](#apache-cassandra)
		- [Use Cases](#use-cases)
		- [Data Modeling with Cassandra](#data-modeling-with-cassandra)
		- [Spark Cassandra Connector](#spark-cassandra-connector)
		- [Serving Layer with Batch and Realtime Views](#serving-layer-with-batch-and-realtime-views)

<!-- /MarkdownTOC -->

# Intro
This image accompanies the Spark course [Applying the Lambda Architecture with Spark, Kafka, and Cassandra](https://www.pluralsight.com/courses/spark-kafka-cassandra-applying-lambda-architecture) on [Pluralsight.com by Ahmad Alkilani](https://www.pluralsight.com/authors/ahmad-alkilani)

The [course](https://www.pluralsight.com/courses/spark-kafka-cassandra-applying-lambda-architecture) aims to get beyond all the hype in the big data world and focus on what really works for building robust highly scalable batch and real-time systems. We will build on an architecture dubbed as the Lambda Architecture which aims to address the complexity of building distributed applications that can work with streaming data just as easily as they can with batch data in a manner that maintains system availability and robustness accounting for human fault tolerance and system updates. In this course we'll string together different technologies that fit well and have been designed by some of the companies with the most demanding data requirements from Facebook, Twitter, and LinkedIn to companies that are leading the way in the design of data processing frameworks like Apache Spark. 

The ability to process data and learn from it has shown benefits in technologies we use every day to advances in studies in medicine. Spark and Spark Streaming play an integral role throughout this course as we look at each individual component, from Apache Kafka, to Cassandra and Hadoop/HDFS and work out details about their architectures that make them good fits for building a system based on the Lambda Architecture. The course continues to build out a full application from scratch starting with building a small application that simulates the production of data in a stream all the way to addressing global state, non-associative calculations, application upgrades and restarts, and finally presenting real-time and batch views in Cassandra.

The course comes with a VM specifically built to allow you to hit the ground running with these technologies including Apache Zeppelin which we use frequently to demonstrate a lot of the code we build.

Please visit the course page for more details [https://www.pluralsight.com/courses/spark-kafka-cassandra-applying-lambda-architecture](https://www.pluralsight.com/courses/spark-kafka-cassandra-applying-lambda-architecture)

## Having problems? See [troubleshooting](https://github.com/aalkilani/spark-kafka-cassandra-applying-lambda-architecture/blob/master/vagrant/troubleshooting.md)

## Fast track to Scala

# Batch layer with Apache Spark
## Fundamentals of batch layer
## Aggregations in Spark
## Introduction to Spark
## Spark Components and Scheduling

# Speed layer with Spark Streaming
## Spark Streaming fundamentals
## Log Producer - Stream Data to Files
## Streaming Aggregations
## Cleaner Code
## Advanced Streaming Operations
### Checkpointing
### Window Operations
### Stateful Transformations
### Streaming Cardinality Estimation
### Algebird Library
## Streaming Aggregations with Apache Zeppelin
# Streaming Ingest with Kafka and Spark Streaming
## Kafka 
### Kafka Producer
### Spark Streaming Integration with Kafka
### Integrate Batch and Streaming
## Persist with Cassandra
### Apache Cassandra
### Use Cases
### Data Modeling with Cassandra
### Spark Cassandra Connector
### Serving Layer with Batch and Realtime Views