## Failure Modes
Silent failures are the most dangerous. Systems that fail loudly can be fixed; systems that fail quietly accumulate debt and erode trust. Design for detection: invariants, assertions, and alarms that trigger before users do.

Deceptive success occurs when metrics trend positively while outcomes degrade. Dashboards should include counter-metrics that capture harm, bias, or operational cost. Feedback loops can either stabilize or destabilize; trace their paths to avoid runaway amplification.

Complex systems rarely fail from a single cause. Look for coupling, hidden dependencies, and insufficient isolation. Postmortems should identify signals that were missed and adjust monitoring accordingly. The goal is not blame but resilience.
