## System Design Template

1. **Problem framing**
   - Define the user, the context, and the desired outcome.
   - State what success and failure look like in measurable terms.

2. **Why it is hard**
   - Identify sources of uncertainty, ambiguity, or scale.
   - Note prior attempts and why they fell short.

3. **Constraints**
   - Enumerate technical, ethical, legal, and operational limits.
   - Include latency, cost, data availability, and safety boundaries.

4. **System overview**
   - Describe the end-to-end architecture and data flows.
   - Highlight trust boundaries and external dependencies.

5. **Intelligence boundary**
   - Specify which components rely on learned behavior versus deterministic logic.
   - Clarify how probabilistic outputs are validated or constrained.

6. **Alternatives rejected**
   - List considered designs and why they were not chosen.
   - Capture tradeoffs to revisit if assumptions change.

7. **Failure modes**
   - Anticipate how the system can misbehave and how to detect it.
   - Plan mitigations, alerts, and safe defaults.

8. **Evaluation**
   - Define metrics, qualitative checks, and experiment plans.
   - Include calibration tests and rollback criteria.

9. **Degradation**
   - Describe how the system should reduce functionality under stress.
   - Outline kill switches and recovery procedures.

10. **Ethical notes**
    - Consider user impact, bias, abuse vectors, and consent.
    - State review processes and accountability.

11. **What I learned**
    - Summarize insights gained during design.
    - Record open issues to revisit after implementation feedback.
