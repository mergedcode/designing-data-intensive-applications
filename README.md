# High-Level Design (HLD) & Distributed Systems Practice Repository

## Core Reading & Practice
- **Primary Book:** *Designing Data-Intensive Applications (DDIA)* — Martin Kleppmann
- **Companion:** *System Design Interview – An Insider's Guide (Vols 1 & 2)* — Alex Xu & Sahn Lam

---

## Core Focus Areas

### 1. Architectural Building Blocks
- Load Balancers (L4 vs. L7, algorithms)
- Caching strategies (Cache-aside, Read/Write-through, Write-back, Eviction policies)
- Databases (SQL vs. NoSQL, Sharding, Replication, Indexing, CAP/PACELC theorem)
- Message Brokers & Event Streaming (Kafka, RabbitMQ)
- Storage Engines (LSM-Tree vs. B+ Tree)
- Distributed Consensus & Transactions (Raft, Paxos, 2PC, Saga pattern)

---

## Classic HLD Practice Blueprints
- [ ] **Distributed URL Shortener** (e.g., TinyURL / Bitly)
- [ ] **Scalable Rate Limiter** (Distributed token bucket with Redis)
- [ ] **Real-time Chat Application** (WebSockets, message queues, presence service)
- [ ] **Video Streaming Platform** (CDN, chunking, transcoding pipeline)
- [ ] **Distributed Key-Value Store** (Consistent hashing, replication, gossip protocol)
- [ ] **Social Media Feed System** (Fan-out on read vs. write, ranking)

