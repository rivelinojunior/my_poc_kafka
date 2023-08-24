# README

Welcome to this Proof of Concept (PoC), where I created a simple Rails API and integrate it with Apache Kafka.

## Prerequisite:
- Ruby `3.2.0`
- Rails `7.0.7.2`
- Apache Kafka cluster

## Apache Kafka
Apache Kafka is an open-source distributed event streaming platform used for building real-time data pipelines and streaming applications. At its core, Kafka acts as a distributed publish-subscribe messaging system. It allows producers to send records (messages) to specific topics, and consumers can subscribe to these topics to receive and process the records in real-time. Kafka retains these records for a configurable period, enabling historical data analysis as well.

If you want to know more about Kafka, I recommend this [free course created by Confluent](https://developer.confluent.io/courses/apache-kafka/events/)

## Karafka

Karafka is a Ruby gem that provides a framework for building message-based applications using Apache Kafka. It's designed to simplify the process of working with Kafka in Ruby applications by abstracting away many of the complexities involved in setting up and managing Kafka consumers and producers.

You can find more info about Karafka at its [github](https://github.com/karafka/karafka)

## Hands-on

- WIP