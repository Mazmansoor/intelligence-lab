## Data Pipelines
Data pipelines move information through collection, validation, transformation, and storage. Flow beats accumulation; unbounded queues hide latency and errors until they explode. Instrument every step: volume, schema changes, null rates, and processing time.

Bottlenecks often stem from implicit contracts. Producers change formats without notice, consumers assume invariants that never existed. Versioned schemas, compatibility tests, and backpressure mechanisms keep pipelines honest.

Fragility increases with silent retries and opaque batch jobs. Prefer small, observable units of work and clear failure alerts. A reliable pipeline is boring: no surprises, predictable timing, and documented handoffs.
