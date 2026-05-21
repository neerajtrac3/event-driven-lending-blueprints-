event-driven-lending-blueprints/
│
├── README.md
│
├── architecture/
│   ├── reference-architecture.md
│   ├── topology-diagram.png
│   ├── event-choreography.md
│   └── lending-lifecycle.md
│
├── event-schemas/
│   ├── application-created.avsc
│   ├── document-submitted.avsc
│   ├── underwriting-completed.avsc
│   ├── offer-generated.avsc
│   ├── loan-booked.avsc
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
