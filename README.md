# Event-Driven Lending Blueprints

Reference architecture and patterns for building event-driven lending platforms, covering the full lifecycle from origination to servicing.

## Objectives

- Define domain events for lending (origination, underwriting, decisioning, fulfilment, servicing)
- Provide event choreography patterns across microservices
- Document resilience patterns (idempotency, retries, DLQ)
- Offer sample producer/consumer implementations

## Repository structure

- `architecture/` – Event-driven reference architecture and diagrams
- `event-schemas/` – Domain event schemas and governance policy
- `blueprints/` – Lifecycle-specific blueprints (origination, underwriting, etc.)
- `resilience/` – Reliability and failure-handling patterns
- `samples/` – Example services and local dev setup
- `use-cases/` – Applied scenarios (real-time decisioning, AML, payments)

## Target audience

- Enterprise and solution architects  
- Lending platform and modernization teams  
- Event-driven architecture practitioners
