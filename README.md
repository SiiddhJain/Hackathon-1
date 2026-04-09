# Hackathon-1

[Project Title: e.g., Continuous Learning for Medical AI]

The Problem
Traditional Transformers (like GPT-4) suffer from "AI amnesia" because they process every request as if it’s the first conversation they’ve ever had. In high-stakes fields like [Your chosen field: e.g., Healthcare], models lose context across long documents, causing them to "drown" or crash after about 12k tokens.

The BDH Solution
Our project explores using The Dragon Hatchling (BDH) architecture to solve this. BDH is a "post-transformer" model that offers:
Constant-Size Memory: It maintains a fixed-size Hebbian state no matter how long the sequence is, allowing it to handle 50k+ tokens where transformers fail.
Live Learning: It learns from new data during inference via Hebbian updates ("neurons that fire together wire together") without needing expensive retraining.
Explainability: Only ~5% of its neurons fire at once, making it easier to trace why a specific decision was made compared to the "black box" of Transformers.

What We Built (Proposed)
[Describe your idea: e.g., "A research assistant that builds a cumulative understanding of 1,000+ medical papers using BDH’s infinite context reasoning"].

Team Members


Demo Video
[Paste your YouTube link here once recorded].
