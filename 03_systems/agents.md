## Agents
Agents exist to pursue goals under uncertainty with partial autonomy. They coordinate actions, gather information, and adapt plans. They are overkill when a deterministic workflow suffices or when human operators can handle branching logic with less risk.

Role clarity prevents thrash. Define what the agent controls, what it must defer, and how it escalates. Feedback channels should be explicit: success criteria, error reporting, and human override. Without these, agents become untrusted noise.

When deploying agents, start narrow. Constrain scope, observe behavior, and expand only with evidence of reliability. Autonomy should be earned through demonstrated stability, not assumed by default.
