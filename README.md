## 🍀 Kafka Mqtt Proof of Solution

This pos provides basic solution to ingest data into mqtt as proxy to kafka confluent using an existing docker image.

### Stack
![Docker](https://img.shields.io/badge/docker-%2357A143.svg?style=for-the-badge&logo=docker&logoColor=white) ![Google_Cloud_Platform](https://img.shields.io/badge/Google_Cloud_Platform-%23000000.svg?style=for-the-badge&logo=google-cloud&logoColor=#FFD700) ![Buildkite](https://img.shields.io/badge/Buildkite-%23000000.svg?style=for-the-badge&logo=Buildkite&logoColor=#FFD700)

### Config
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
