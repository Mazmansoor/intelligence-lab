## Benchmarks
Benchmarks offer comparability but rarely mirror reality. They lag behind changing environments and can incentivize overfitting to test sets. Treat benchmark performance as a starting point, not a verdict.

When using benchmarks, document the gap between the benchmark setting and production conditions: data sources, constraints, failure tolerance. Run ablations to understand which components drive scores, and verify that improvements translate to real users.

Diversify evaluation. Combine synthetic tests, live traffic experiments, and adversarial scenarios. A system that only shines on benchmarks is unprepared for the surprises of deployment.
