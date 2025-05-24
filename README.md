# 🐳 Local Development Environment (Docker Compose)

This repository contains a full local development environment powered by Docker Compose. It includes:

- ✅ Databases: MySQL & PostgreSQL
- ✅ Message Brokers: Apache Kafka & RabbitMQ
- ✅ Search: Elasticsearch (dev & prod setups)
- ✅ UI for Elasticsearch: Kibana

---

## 📦 Services Included

| Service              | Port(s)         | Description                             | --  |
| -------------------- | --------------- | --------------------------------------- | --- |
| MySQL                | `3306`          | Relational DB for transactional storage |
| PostgreSQL           | `5432`          | Another relational DB alternative       |
| Kafka                | `9092`, `29092` | Distributed event streaming platform    |
| RabbitMQ             | `5672`, `15672` | Lightweight message broker              |
| Elasticsearch (Dev)  | `9200`          | Dev ES node with no security            |
| Elasticsearch (Prod) | `9201`          | Production-style ES cluster (secured)   |
| Kibana               | `5601`          | Elasticsearch GUI                       |

---
