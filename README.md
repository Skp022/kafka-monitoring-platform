# Kafka Monitoring Platform

## Overview

Built a real-time Kafka Monitoring and Alerting Platform using Docker Compose, Kafka, Zookeeper, Prometheus, Grafana, Kafka Exporter, and Alertmanager.

## Architecture

Kafka Broker
→ Kafka Exporter
→ Prometheus
→ Grafana
→ Alertmanager

## Technologies Used

* Apache Kafka
* Zookeeper
* Kafka Exporter
* Prometheus
* Grafana
* Alertmanager
* Docker Compose

## Features

* Kafka broker monitoring
* Kafka topic monitoring
* Producer and consumer testing
* Real-time metrics collection
* Grafana dashboards
* Alerting with Alertmanager

## Validation Performed

* Created Kafka topics
* Produced messages using kafka-console-producer
* Consumed messages using kafka-console-consumer
* Verified metrics in Prometheus
* Visualized Kafka metrics in Grafana

## Key Commands

Create Topic:
kafka-topics --create --topic test-topic --bootstrap-server localhost:9092 --partitions 1 --replication-factor 1

Producer:
kafka-console-producer --topic test-topic --bootstrap-server localhost:9092

Consumer:
kafka-console-consumer --topic test-topic --from-beginning --bootstrap-server localhost:9092
