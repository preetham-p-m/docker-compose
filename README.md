# 🐳 Local Development Environment (Docker Compose)

This repository contains a full local development environment powered by Docker Compose. It includes:

- ✅ Databases: MySQL & PostgreSQL
- ✅ Message Brokers: Apache Kafka & RabbitMQ
- ✅ Search: Elasticsearch (dev & prod setups)
- ✅ UI for Elasticsearch: Kibana

---

## 📦 Services Included

### MySQL

| Service | Port(s) | Description                             |
| ------- | ------- | --------------------------------------- |
| MySQL   | `3306`  | Relational DB for transactional storage |

### PostgreSQL

| Service    | Port(s) | Description                       |
| ---------- | ------- | --------------------------------- |
| PostgreSQL | `5432`  | Another relational DB alternative |

### Kafka

| Service      | Port(s) | Description                          |
| ------------ | ------- | ------------------------------------ |
| Kafka node 1 | `9092`  | Distributed event streaming platform |
| Kafka node 2 | `9094`  | Distributed event streaming platform |
| Kafka node 3 | `9096`  | Distributed event streaming platform |

### RabbitMQ

| Service  | Port(s)         | Description                |
| -------- | --------------- | -------------------------- |
| RabbitMQ | `5672`, `15672` | Lightweight message broker |

### Elastic Search

| Service              | Port(s) | Description                           |
| -------------------- | ------- | ------------------------------------- |
| Elasticsearch (Dev)  | `9200`  | Dev ES node with no security          |
| Elasticsearch (Prod) | `9201`  | Production-style ES cluster (secured) |
| Kibana               | `5601`  | Elasticsearch GUI                     |

## Redis

| Service                   | Port(s) | Description          |
| ------------------------- | ------- | -------------------- |
| Redis Cluster node 1      | `7001`  | Redis 3 node cluster |
| Redis Cluster node 2      | `7002`  | Redis 3 node cluster |
| Redis Cluster node 3      | `7003`  | Redis 3 node cluster |
| Redis Standalone instance | `6379`  | Redis Instance       |

---
