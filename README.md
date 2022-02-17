## 🍀 Kafka Mqtt Proof of Solution

This pos provides basic solution to ingest data into mqtt as proxy to kafka confluent using an existing docker image.

### Stack
![Docker](https://img.shields.io/badge/docker-%2357A143.svg?style=for-the-badge&logo=docker&logoColor=white) ![kafka](https://img.shields.io/badge/kafka-%2357A143.svg?style=for-the-badge&logo=kafka&logoColor=white) ![MQTT](https://img.shields.io/badge/mqtt-%2357A143.svg?style=for-the-badge&logo=mqtt&logoColor=white) 


### Configs
```
KAFKA_MQTT_BOOTSTRAP_SERVERS: ""
KAFKA_MQTT_TOPIC_REGEX_LIST: kafka-topic:mqtt
KAFKA_MQTT_KEY_DESERIALIZER: org.apache.kafka.common.serialization.StringDeserializer
KAFKA_MQTT_VALUE_DESERIALIZER: org.apache.kafka.common.serialization.StringDeserializer
KAFKA_MQTT_LISTENERS: 0.0.0.0:1883
KAFKA_MQTT_PRODUCER_CLIENT_ID: pos.cnd
KAFKA_MQTT_PRODUCER_GROUP_ID: mortiz
KAFKA_MQTT_PRODUCER_SECURITY_PROTOCOL: SASL_SSL
KAFKA_MQTT_PRODUCER_SASL_MECHANISM: PLAIN
KAFKA_MQTT_PRODUCER_SASL_JAAS_CONFIG: org.apache.kafka.common.security.plain.PlainLoginModule required username="**" password="**";
```


### Support
reachout to ortizmark905@gmail.com if you need help or want to develop related to this. 
