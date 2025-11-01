# 🏗️ System Design
- Focus: LLD & HLD practice with real-world examples  
- Learn from: **Gaurav Sen**, **Code Karle**, **ByteByteGo**, and **Concept & Coding by Shrayansh**

---

## 🔹 Concept & Coding — by Shrayansh

### 🎯 Low Level Design (LLD)
- **Playlist:** [Low Level Design from Basics to Advanced](https://www.youtube.com/playlist?list=PL6W8uoQQ2c61X_9e6Net0WdYZidm7zooW)  
- **Overview:** Covers core OOP concepts, design patterns, and class design for interview-oriented system design questions.
- [Gitlab - Low Level Design](https://gitlab.com/shrayansh8/lld-lowleveldesign/-/tree/main/src/main/java/com/conceptcoding?ref_type=heads)
- [Gitlab - Low Level Design Interview](https://gitlab.com/shrayansh8/interviewcodingpractise/-/tree/main/src/main/java/com/conceptandcoding/LowLevelDesign?ref_type=heads)

### 🧠 High Level Design (HLD)
- **Playlist:** [High Level Design from Basics to Advanced](https://www.youtube.com/playlist?list=PL6W8uoQQ2c63W58rpNFDwdrBnq5G3EfT7)  
- **Overview:** Explains scalable architecture, API design, load balancing, and database sharding concepts.

---

## 🔹 Gaurav Sen

- **Playlist:** [System Design Playlist](https://www.youtube.com/playlist?list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX)  
- **Overview:** Deep dives into core distributed system concepts like consistency, CAP theorem, caching, queues, and popular product architectures (e.g., YouTube, Uber, Twitter).

---

## 🔹 Code Karle

- **Playlist:** [System Design by Code Karle](https://www.youtube.com/playlist?list=PLhgw50vUymyckXl3D1IlXoVl94wknJfUC)  
- **Overview:** Practical breakdowns of real-world system designs — focuses on simplicity, trade-offs, and interview-ready clarity.

---

## 🔹 ByteByteGo

- **Playlist:** [System Design Fundamentals](https://www.youtube.com/playlist?list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf)  
- **Overview:** Visually rich explanations of distributed systems, scalability, and modern cloud architecture patterns.

---

## 🧭 System Design Roadmap

### 🧱 Overview

| **System Design** |   |   |
|--------------------|---|---|
| **HLD** | **LLD** |
| Database | Design API |
| Message Queue | Class Diagram |
| Cache | Models |

---

### 🔹 High Level Design (HLD)

#### **Functional Requirements**
- Users can signup & login  
- Users can buy a subscription  
- User can play/pause a video  

#### **Non-Functional Requirements**
- Secure system with authentication/authorization  
- Low latency for videos  
- Scalable system  

---

#### **Step 1: Fundamentals**
- Serverless vs Serverful  
- Horizontal vs Vertical Scaling  
- What are threads?  
- What are pages?  
- How does the internet work?  

#### **Step 2: Databases**
- SQL vs NoSQL DBs  
- In-memory DBs  
- Data Replication & Migration  
- Data Partitioning  
- Sharding  

#### **Step 3: Consistency vs Availability**
- Data Consistency & its levels  
- Isolation & its levels  
- CAP Theorem  

#### **Step 4: Cache**
- What is Cache? (Redis, Memcached)  
- Write Policies: write back, through & around  
- Replacement Policies: LFU, LRU, Segmented LRU etc.  
- Content Delivery Networks (CDNs)  

#### **Step 5: Networking**
- TCP vs UDP  
- What is HTTP (1/2/3) & HTTPS  
- WebSockets  
- WebRTC & video streaming  

#### **Step 6: Load Balancers**
- Load Balancing Algorithms (Stateless & Stateful)  
- Consistent Hashing  
- Proxy & Reverse Proxy  
- Rate Limiting  

#### **Step 7: Message Queues**
- Asynchronous Processing (Kafka, RabbitMQ)  
- Publisher-Subscriber Model  

#### **Step 8: Monoliths vs Microservices**
- Why Microservices?  
- Concept of 'Single Point of Failure'  
- Avoiding Cascading Failures  
- Containerization (Docker)  
- Migrating to Microservices  

#### **Step 9: Monitoring & Logging**
- Logging events & monitoring metrics  
- Anomaly Detection  

#### **Step 10: Security**
- Tokens for auth  
- SSO & OAuth  
- Access Control Lists & Rule Engines  
- Encryption  

#### **Step 11: System Design Tradeoffs**
- Push vs Pull architecture  
- Consistency vs Availability  
- SQL vs NoSQL DBs  
- Memory vs Latency  
- Throughput vs Latency  
- Accuracy vs Latency  

#### **Step 12: Practice, Practice, Practice**
1. YouTube  
2. Twitter  
3. WhatsApp  
4. Uber  
5. Amazon  
6. Dropbox / Google Drive  
7. Netflix  
8. Instagram  
9. Zoom  
10. Booking.com / Airbnb  

---

### 🔹 Low Level Design (LLD)

#### **Step 1: Object Oriented Programming**
- Encapsulation  
- Abstraction  
- Inheritance  
- Polymorphism  
- SOLID Principles  

#### **Step 2: Design Patterns**
- Creational (Singleton, Factory etc.)  
- Structural (Proxy, Bridge etc.)  
- Behavioral (Strategy, Command, Observer etc.)  

#### **Step 3: Concurrency & Thread Safety**
- Thread safe injection  
- Locking mechanisms  
- Producer-Consumer  
- Race conditions & synchronization  

#### **Step 4: UML Diagrams**

#### **Step 5: APIs**
- API Design  
- Request/Response Object Modeling  
- Versioning & Extensibility  
- Clean Code Principles: DRY, SRP etc.  
- Avoiding God Classes  

#### **Step 6: Common LLD Problems**
1. Design a Tic-tac-toe or Chess Game  
2. Design a Splitwise App  
3. Design a Parking Lot  
4. Design an Elevator System with Multiple Lifts  
5. Design a Notification System  
6. Design a Food Delivery App  
7. Design a Movie Ticket Booking System  
8. Design a URL Shortener  
9. Design a Logging Framework  
10. Design a Rate Limiter  

---

💡 **Tip:**  
Follow this order for learning:
1. **Low Level Design (Shrayansh)** → solidify fundamentals.  
2. **High Level Design (Shrayansh)** → learn scalability and components.  
3. **Gaurav Sen & Code Karle** → dive into real-world systems.  
4. **ByteByteGo** → reinforce concepts with visual summaries.
