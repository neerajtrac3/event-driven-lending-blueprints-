# Event-Driven-Lending-Blueprints-
Event‑driven architecture blueprints for lending lifecycle automation and real‑time processing.

event-driven-lending-blueprints/
│
├── README.md
├── architecture/
│   ├── reference-architecture.md
│   ├── topology-diagram.png
│   └── choreography-vs-orchestration.md
│
├── event-schemas/
│   ├── application-created.avsc
│   ├── underwriting-completed.avsc
│   └── schema-governance-policy.md
│
├── blueprints/
│   ├── origination/
│   ├── underwriting/
│   ├── decisioning/
│   ├── fulfilment/
│   └── servicing/
│
├── resilience/
│   ├── idempotency-patterns.md
│   ├── retry-strategy.md
│   └── dlq-runbook.md
│
├── samples/
│   ├── producer-sample/
│   └── consumer-sample/
│
└── use-cases/
    ├── real-time-decisioning.md
    ├── aml-event-pipeline.md
    └── payment-processing.md
