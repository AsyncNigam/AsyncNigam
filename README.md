# Nigam Prasad Sahoo

Backend Software Engineer focused on distributed systems, event-driven architectures, and high-reliability APIs. 

Currently building backend services in Node.js, NestJS, and TypeScript, with a focus on fault isolation, transactional data pipelines, and zero-knowledge systems.

[GitHub](https://github.com/AsyncNigam) · [LinkedIn](https://www.linkedin.com/in/nigam-prasad-sahoo-b0768034a/) · [LeetCode](https://leetcode.com/u/AsyncNigam143/) · [Email](mailto:nigam.nps@gmail.com)

---

### Core Focus & Systems

- **LeetCAD — Event-Driven CAD Assessment Engine**  
  NestJS, RabbitMQ, PostgreSQL, Redis, Cloudflare R2, Socket.io, Azure  
  - Reliable event delivery to RabbitMQ via PostgreSQL Transactional Outbox pattern (`SKIP LOCKED` polling).
  - Claim-Check pattern for 50MB CAD uploads using presigned R2 URLs to keep API memory footprint flat.
  - Sandboxed C++ OpenCASCADE evaluations inside Python worker subprocesses with 30s timeouts to isolate `SIGSEGV` faults from the main daemon.
  - Cross-service tracing instrumented via OpenTelemetry; duplicate task runs prevented with Redis fencing tokens.

- **Quantum Safe Messenger — Zero-Knowledge Relay Infrastructure**  
  Node.js, Express, Socket.io, Redis, PostgreSQL, Docker  
  - Stateless relay infrastructure ensuring zero server access to plaintext or cryptographic private keys.
  - Hybrid post-quantum key exchange (ML-KEM-768) and AES-256-GCM symmetric encryption with Ed25519/ML-DSA signatures.
  - Ephemeral message delivery via Redis TTL queues and metadata-only push triggers via Firebase Cloud Messaging.
  - Native client published on Google Play Store; client identity managed using deterministic SHA-256 hashes.

---

### Technical Proficiencies

- **Languages:** TypeScript, JavaScript, Python, Java, SQL, C++
- **Backend & Distributed Systems:** Node.js, NestJS, Express.js, RabbitMQ, REST APIs, WebSockets, OAuth 2.0
- **Databases & Storage:** PostgreSQL, Redis, MongoDB, TypeORM, Sequelize, Cloudflare R2
- **Infrastructure & Observability:** Docker, Azure, Linux, GitHub Actions, OpenTelemetry, Winston

---

### Background

- **Experience:** Software Engineering Intern @ Tech Squadrons (Jun 2026 – Present)
- **Problem Solving:** 350+ algorithmic problems solved across LeetCode and GeeksforGeeks
- **Academics:** B.Tech in CSE at Indira Gandhi Institute Of Technology (2024–2028, GPA: 9.70/10.0)
