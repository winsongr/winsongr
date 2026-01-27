# Winson GR
**Backend Systems Engineer | Distributed Systems & Fintech**

I design, build, and operate backend systems where data integrity, retries, and failure handling are non-negotiable. I specialize in building boring systems that don't break under load.

---

## Engineering Impact

- Built and operated backend workflows supporting **100k+ paid subscribers** in revenue-critical environments with strict consistency guarantees.
- Reduced infrastructure and API costs by **$48k/year** by migrating third-party workflows to in-house PostgreSQL-backed systems.
- Improved query performance by **~90%** through schema design, denormalization, and index tuning in financial data pipelines.
- Reduced LLM token costs by **~30%** using semantic caching and request-aware model routing.

---

## Selected Systems

### Transaction Engine
FSM-based transactional workflow engine designed to prevent state corruption in payment and finance workflows.

- Enforces exactly-once state transitions using idempotency keys
- Uses the transactional outbox pattern for safe event publishing
- Built to survive retries, crashes, and duplicate events

→  [View repository](https://github.com/winsongr/transaction-engine) 

### Async RAG Ingestion Engine
Deterministic async ingestion pipeline for large-scale document processing.

- Idempotent vector indexing with failure-safe retries
- DLQ-backed recovery for rate limits and partial failures
- Designed for predictable cost and zero data loss

→  [View repository](https://github.com/winsongr/async-rag-ingestion-engine) 

---

## Focus
**Python · Go · PostgreSQL · Kafka · Redis**  
Distributed systems · Event-driven architectures · Reliability patterns

**LinkedIn:** [linkedin.com/in/winsongr](https://linkedin.com/in/winsongr)  
**LeetCode:** [leetcode.com/u/winsongr](https://leetcode.com/u/winsongr)
