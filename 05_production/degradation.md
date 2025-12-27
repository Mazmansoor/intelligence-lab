## Degradation
Systems should fail gracefully. When resources are scarce or dependencies falter, degrade service in controlled ways: reduce features, lower quality, or queue requests instead of crashing. Define tiers of service and map them to triggers.

Degradation policies must be rehearsed. Simulate outages, throttle dependencies, and verify that user-facing messaging remains clear. Prefer predictable behavior to opportunistic improvisation by models or downstream services.

Shutdown paths matter. In extreme cases, the safest action is to refuse requests. Build kill switches with proper authorization and logging. After recovery, conduct reviews to adjust thresholds and automation.
