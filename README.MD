### Motivation

[Apache Qpid](https://qpid.apache.org/index.html) is an AMQP broker. Tests have been made, and Streamsets Data Collector’s (SDC) standard stages RabbitMQ and VMS are not capable of integrating with Apache Qpid. Another approach, which is discussed below, is by using Groovy evaluator. 

Java-based [VMS client](https://qpid.apache.org/components/jms/index.html) library can be integrated into SDC to read messages from Qpid queues or send messages to Qpid.
