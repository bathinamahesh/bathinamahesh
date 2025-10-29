# 🧩 Database Internals

A deep dive into how modern databases work — from query engines and storage layers to distributed internals.

---

## 🎥 1️⃣ Video Learning Series
- 📺 **Database Systems Concepts & Internals (CMU)**
  - [YouTube Playlist (CMU Database Systems)](https://www.youtube.com/playlist?list=PLSE8ODhjZXjbj8BMuIrRcacnQh20hmY9g)
  - 🎓 Covers query execution, transaction management, storage, and indexing in PostgreSQL-style architectures.

---

## 🗃️ 2️⃣ Relational Databases (RDBMS)

### 🐘 PostgreSQL Internals
- 🔍 Deep dive into PostgreSQL architecture — storage engine, WAL, MVCC, planner, and executor.
- 📖 **Book:** [*Database Internals — A Deep Dive into How Distributed Data Systems Work*](https://www.amazon.ca/Database-Internals-Deep-Distributed-Systems-ebook/dp/B07XW76VHZ)
- 🧠 Topics to Explore:
  - Buffer management & shared memory
  - Checkpoints & Write-Ahead Logging (WAL)
  - Query planner & executor pipeline
  - MVCC and concurrency control
  - Index structures (B-Tree, GiST, GIN, BRIN)
  - Extension system (FDW, C extensions)

---

## 💾 3️⃣ Non-Relational Databases (NoSQL)

### ⚡ Redis Internals
- 🧩 Learn Redis as an in-memory data structure store — persistence, replication, clustering.
- 🧠 Topics to Explore:
  - RDB vs AOF persistence
  - Event loop & single-threaded model
  - Pub/Sub and Streams
  - Cluster sharding & failover

---

## 🧠 4️⃣ Deep-Dive Concepts (General)
- ⚙️ **Storage Engines:** LSM Trees, B-Trees, Heap vs Columnar storage  
- 🔄 **Consistency & Transactions:** ACID, CAP, isolation levels, replication lag  
- ☁️ **Distributed Databases:** Raft, Paxos, sharding, partition tolerance  
- 🧮 **Query Optimizers:** Cost estimation, statistics, join order selection  
- 💡 **Internals Comparison:** PostgreSQL vs MySQL InnoDB vs Redis vs MongoDB  

---

💬 *Tip:* Start with the **YouTube series** for conceptual grounding → move to **PostgreSQL internals** for hands-on depth → finish with **Redis internals** and **Database Internals book** for distributed design mastery.
