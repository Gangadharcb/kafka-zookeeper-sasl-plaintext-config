notes on kafka and zookeeper configration SASL_PLAINTEXT

Tested with 
Kafka version: 2.12-2.3.0
Zookeeper version: 3.5.5

how to setup SASL_PLAINTEXT auth between. 
* kafka <-> kafka
* kafka <-> zookeeper
* zookeer <-> zookeeper


big chunk of configuration is taken by. 
https://stackoverflow.com/questions/43469962/kafka-sasl-zookeeper-authentication

This does need some minor changes while configuring standalone version of zookeeper. 
