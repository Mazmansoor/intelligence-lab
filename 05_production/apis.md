## APIs
APIs are contracts, not conveniences. They define what callers can rely on and what providers must honor. Stability matters: breaking changes cascade through dependent systems and erode trust.

Design APIs with clear ownership, versioning, and deprecation policies. Document expectations about latency, idempotency, and error semantics. Provide explicit guarantees about data formats and authentication.

Instrument APIs for usage patterns, error rates, and abuse signals. Treat each endpoint as a surface that must be defended and maintained over time, not as a one-time integration.
