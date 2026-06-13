A high-performance, scalable **NestJS** microservice designed for robust **Apache Kafka** event streaming.

## 🚀 Overview
This service acts as a specialized producer/consumer in a distributed Kafka ecosystem. It is built to ensure reliable message processing, fault tolerance, and seamless integration with Kafka brokers.

---

## 🛠 Tech Stack
* **Framework:** NestJS
* **Language:** TypeScript
* **Messaging:** Apache Kafka (via `@nestjs/microservices`)
* **Environment:** Node.js

---

## ⚙️ Kafka Architecture
This microservice follows a producer/consumer pattern.

* **Topics:** Defines the channels for data ingestion and egress.
* **Consumer Groups:** Uses specific `groupId` configurations to manage load balancing across instances.
* **Messaging Pattern:** Supports both fire-and-forget (`emit`) and request-response patterns.

---

## 📦 Project Setup

```bash
$ npm install