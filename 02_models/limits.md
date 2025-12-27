## Limits
Models mislead when deployed outside their training distribution, when incentives reward the wrong outputs, or when their uncertainty is ignored. Hallucinations, mode collapse, and overfitting are symptoms of deeper issues: insufficient data quality, weak evaluation, or misaligned objectives.

Cataloging limits is a defensive practice. List the domains where the model underperforms, the inputs that trigger instability, and the signals that detect drift. Track how limits change over time as data, infrastructure, and objectives evolve. Treat limits as design artifacts, not as embarrassing footnotes.

When limits intersect with safety or ethics, prefer hard stops to graceful degradation. If the system cannot maintain integrity, it should decline rather than improvise.
