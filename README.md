# Winson GR
**Senior Backend Engineer | Python · Go · Distributed Systems · Fintech & AI Infrastructure**

I build production backend systems where **data integrity, failure recovery, and operational reliability are critical**.

My work focuses on distributed architectures, financial data pipelines, and AI-powered backend systems designed to remain stable under concurrency, retries, and partial failures.

I specialize in building **boring systems that don’t break under load.**

---

## Engineering Impact

• Backend systems supporting **100K+ paid users** in revenue-critical environments with strict consistency guarantees  
• Reduced infrastructure and API costs by **$48K/year** by replacing third-party services with in-house PostgreSQL workflows  
• Improved query performance by **~90%** in financial data pipelines serving **3M monthly users** through schema redesign and indexing strategies  
• Reduced LLM inference costs by **~30%** using semantic caching and request-aware model routing  

---

## Selected Systems

### Transaction Engine

Distributed workflow engine designed to prevent invalid state transitions in financial systems.

Key design ideas:

• Exactly-once state transitions using **idempotency keys**  
• **Transactional outbox pattern** to safely publish events from PostgreSQL  
• **Optimistic locking** to prevent concurrent state corruption  

Built to survive **retries, crashes, and duplicate events** in distributed financial workflows.

→ [View repository](https://github.com/winsongr/transaction-engine)

---

### Async RAG Ingestion Engine

Large-scale ingestion pipeline for document processing and vector indexing.

Key design ideas:

• **Idempotent document ingestion** preventing duplicate embeddings  
• **Dead Letter Queue (DLQ)** recovery for rate limits and partial failures  
• Deterministic indexing enabling safe retries without data corruption  

Designed for **predictable cost, high throughput, and zero data loss** in production AI systems.

→ [View repository](https://github.com/winsongr/async-rag-ingestion-engine)

---

## Technical Focus

**Core stack**  
Python · Go · PostgreSQL · Kafka · Redis · FastAPI  

**Architecture patterns**  
Event-driven systems · Idempotency · Transactional Outbox · Async processing · Failure recovery  

**Currently exploring**  
Go for high-throughput backend services and distributed API systems

---

**LinkedIn:** https://linkedin.com/in/winsongr  
**LeetCode:** https://leetcode.com/u/winsongr
