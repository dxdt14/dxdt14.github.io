---
title: "Continual Instruction Tuning via Increasing Experts"
collection: publications
category: peer_reviewed
authors: 'X. Wu, M. Hartman<sup>*</sup>, <strong>V. A. Jayaraman</strong><sup>*</sup>, and L. R. Varshney'
venue_status: 'IEEE Journal of Selected Topics in Signal Processing'
excerpt: 'A switching network for alleviating catastrophic forgetting during continual instruction tuning of large language models.'
date: 2026-02-23
paperurl: '/files/switchcit.pdf'
citation: 'X. Wu, M. Hartman, V. A. Jayaraman and L. R. Varshney, "Continual Instruction Tuning via Increasing Experts," in IEEE Journal of Selected Topics in Signal Processing, doi: 10.1109/JSTSP.2026.3666304.'
---

Large language models (LLMs) and multimodal models (MMs) have exhibited impressive capabilities in various domains, particularly in general language understanding and visual reasoning. However, these models, trained on massive data, may not be finely optimized for specific tasks triggered by instructions. Continual instruction tuning is crucial to adapting a large model to evolving tasks and domains, ensuring their effectiveness and relevance across a wide range of applications. In the context of continual instruction tuning, where models are sequentially trained on different tasks, catastrophic forgetting can occur, leading to performance degradation on previously learned tasks. This work addresses the catastrophic forgetting in continual instruction learning through a switching mechanism for routing computations to parameter-efficient tuned expert models. We demonstrate the effectiveness of our method through experiments on continual instruction tuning of different natural language generation tasks and vision-language tasks. We also showcase the advantages of our proposed method in terms of efficiency, scalability, portability, and privacy preservation.
