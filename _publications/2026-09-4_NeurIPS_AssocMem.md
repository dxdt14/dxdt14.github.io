---
title: "Context-Gated Associative Retrieval: From Theory to Transformers"
collection: publications
category: manuscripts
excerpt: 'Under Review for NeurIPS 2026. We propose a two-stage energy-based associative memory where context reshapes the retrieval landscape, provably increasing separation and inducing sparsity for improved recall.'
date: 2026-05-04
paperurl: 'https://arxiv.org/abs/2605.10970'
citation: 'Choraria, M., Gerogiannis, A., Jayaraman, V.A., Mani, A., & Varshney, L.R. (2026). Context-Gated Associative Retrieval: From Theory to Transformers'
---

Hopfield networks and their generalizations have established deep connections among biological associative memories, statistical physics, and transformers. Yet most models treat retrieval as a fixed query-to-memory mapping, ignoring the role of external context in recall. In this work, we propose a two-stage associative memory architecture, wherein a context-gate subcircuit reshapes the retrieval energy landscape before and during recall. We show theoretically that context gating increases inter-memory separation while inducing sparsity, translating into exponential improvements in retrieval. Crucially, we prove that the system admits a unique self-consistent fixed point, revealing that the resulting retrieval state is driven by both a direct contextual bias and a second-order retrieval-gate feedback loop. We then bridge this theory to transformers; specifically, we evaluate a first-order approximation on Llama-3, confirming that in-context learning acts as context-gated retrieval. Native dynamics mirror our theory: context localizes a memory subspace, enabling the zero-shot query to cleanly discriminate. Ultimately, this framework provides a mechanistic link between associative memory theory and LLM phenomenology.

