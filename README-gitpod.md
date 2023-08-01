# Python Fake Data Producer for Apache Kafka®

## Gitpod 

`avn user login --token`

`export token=<your token>`

If you haven't yet create a kafka service : 

```
avn service create demo-kafka               \
    -t kafka                                \
    --cloud google-europe-west1             \
    -p startup-2                            \
    -c kafka.auto_create_topics_enable=true \
    -c kafka_rest=true                    

```

## Description

**Python Fake Data Producer for Apache Kafka®** is a complete demo app allowing you to quickly produce a Python fake Pizza-based streaming dataset and push it to an Apache Kafka® topic. It gives an example on how easy is to create great fake streaming data to feed Apache Kafka.

* **Apache Kafka**: a [distributed streaming platform](https://kafka.apache.org/)
* **Topic**: all Apache Kafka records are organised into topics, you can think of a topic like an event log or a table if you're familiar with databases.
* **Apache Kafka Producer**: an entity/application that publishes data to Apache Kafka

An Apache Apache Kafka cluster can be created in minutes in any cloud of your choice using [Aiven.io console](https://console.aiven.io/signup?utm_source=github&utm_medium=organic&utm_campaign=blog_art&utm_content=post).

For more informations about the code building blogs check the [blog post](https://aiven.io/blog/create-your-own-data-stream-for-kafka-with-python-and-faker?utm_source=github&utm_medium=organic&utm_campaign=blog_art&utm_content=post)
