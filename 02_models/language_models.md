## Language Models
Language models predict text continuations. They excel at fluency, pattern completion, and synthesizing from observed data. They do not understand in the human sense; they operate on statistical associations. Fluency can mask gaps in grounding, leading to confident fabrication.

Failure modes include hallucination, misplaced certainty, and sensitivity to prompt phrasing. Guardrails should combine retrieval, validation, and user-visible uncertainty. Use them as probabilistic components rather than oracles.

Language models shine when tasks involve summarization, drafting, or exploration under human oversight. They struggle when exactness, traceability, or high-stakes decisions are required. Design systems that expose their limits and route critical steps through deterministic checks.
