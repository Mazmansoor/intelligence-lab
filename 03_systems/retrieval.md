## Retrieval
Retrieval bridges stored knowledge and active tasks. Relevance and recall are competing priorities; tune them according to the stakes of missing information versus including noise. Staleness is a silent failure: outdated results can look correct yet mislead decisions.

Grounding requires provenance. Store why an item was retrieved, when it was last verified, and what query produced it. Feedback loops—acceptance, rejection, corrections—should update both the retrieval index and the upstream data quality processes.

In high-risk contexts, retrieval should be conservative and auditable. When paired with generative models, retrieval must counter hallucination by providing hard references and enforcing citation in outputs.
