# Designing Data-Intensive Applications (DDIA) - System Design & Distributed Systems

Notes, architectural blueprints, and practical implementations based on **_Designing Data-Intensive Applications_** by Martin Kleppmann.

---

## 🎯 Objective
- Understand the core principles behind reliable, scalable, and maintainable data systems.
- Master trade-offs in distributed storage, replication, partitioning, and consensus.
- Prepare for High-Level Design (HLD) engineering problems with rigorous architectural trade-offs.

---

## 📂 Core Curriculum & Chapters

### Part I: Foundations of Data Systems
- [ ] **Chapter 1: Reliable, Scalable, and Maintainable Applications**
  - Fault tolerance, SLAs, SLOs, latency percentiles (p95, p99, p99.9).
- [ ] **Chapter 2: Data Models and Query Languages**
  - Relational vs. Document vs. Graph data models.
- [ ] **Chapter 3: Storage and Retrieval**
  - Log-structured storage (LSM-Trees, SSTables) vs. B-Trees.
  - In-memory data stores, OLTP vs. OLAP, column-oriented storage.
- [ ] **Chapter 4: Encoding and Evolution**
  - Formats: JSON, XML, Protocol Buffers, Avro, Thrift; forward & backward compatibility.

### Part II: Distributed Data
- [ ] **Chapter 5: Replication**
  - Single-leader, multi-leader, and leaderless replication.
  - Replication lag, read-after-write consistency, monotonic reads, quorum reads/writes ($W + R > N$).
- [ ] **Chapter 6: Partitioning / Sharding**
  - Partitioning by key range vs. hash of key; consistent hashing, secondary indexes.
- [ ] **Chapter 7: Transactions**
  - ACID guarantees, isolation levels (Read Committed, Snapshot Isolation, Serializable).
- [ ] **Chapter 8: The Trouble with Distributed Systems**
  - Network partitions, clock skew, Byzantine faults, split-brain.
- [ ] **Chapter 9: Consistency and Consensus**
  - Linearizability, total order broadcast, distributed transactions (2PC), consensus algorithms (Raft, Paxos).

### Part III: Derived Data
- [ ] **Chapter 10: Batch Processing**
  - MapReduce, dataflow engines (Spark, Flink).
- [ ] **Chapter 11: Stream Processing**
  - Event streaming (Kafka), windowing, stream joins, exactly-once processing.
- [ ] **Chapter 12: The Future of Data Systems**
  - Unbundling databases, data integration, end-to-end correctness.

---

## 🏗️ Hands-On HLD Blueprints
- [ ] **Distributed Key-Value Store** (Consistent hashing, replication, gossip protocol)
- [ ] **Distributed Rate Limiter** (Redis token bucket, sliding window counter)
- [ ] **URL Shortener** (Base62 encoding, distributed ID generation via Snowflake)
- [ ] **Real-time Messaging System** (WebSockets, pub/sub, presence servers)
- [ ] **Video Streaming Platform** (Transcoding pipeline, chunk storage, CDN caching)

---

## 📚 References & Resources
- **Author's Companion Site:** [dataintensive.net](https://dataintensive.net/)
- **References & Errata:** [github.com/ept/ddia-references](https://github.com/ept/ddia-references)
