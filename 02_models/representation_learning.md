## Representation Learning
Representations compress observations into usable structure. Good representations separate signal from noise and make downstream tasks simpler. They also hide information: whatever is discarded cannot be recovered, and the choice of what to preserve encodes judgment about what matters.

Learning representations shifts effort from manual feature crafting to designing objectives and data curation. It introduces new failure modes: shortcut learning, spurious correlations, and entanglement that makes debiasing difficult. Interpretability requires probing and stress testing, not just visualizing embeddings.

Use representation learning when data richness overwhelms manual design or when transfer across tasks is valuable. Document the training data, objectives, and evaluation so future changes can be traced to their impact on the learned space.
