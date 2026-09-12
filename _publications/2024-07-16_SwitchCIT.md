---
title: "SwitchCIT: Switching for Continual Instruction Tuning of Large Language Models"
collection: publications
category: peer_reviewed
authors: 'X. Wu, M. Hartman<sup>*</sup>, <strong>V. A. Jayaraman</strong><sup>*</sup>, and L. R. Varshney'
venue_status: 'IEEE Journal of Selected Topics in Signal Processing'
excerpt: 'A switching network for alleviating catastrophic forgetting during continual instruction tuning of large language models.'
date: 2024-07-16
paperurl: 'https://arxiv.org/abs/2407.11780'
citation: 'Wu, X., Hartman, M.*, Jayaraman, V. A.*, & Varshney, L. R. (2024, July 16). SwitchCIT: Switching for continual instruction tuning of large language models. arXiv.org. https://arxiv.org/abs/2407.11780'
---

Large language models (LLMs) have exhibited impressive capabilities in various domains, particularly in general language understanding. However these models, trained on massive text data, may not be finely optimized for specific tasks triggered by instructions. Continual instruction tuning is crucial to adapt LLMs to evolving tasks and domains, ensuring their effectiveness and relevance across a wide range of applications. In the context of continual instruction tuning, where models are sequentially trained on different tasks, catastrophic forgetting can occur, leading to performance degradation on previously learned tasks. This work addresses the catastrophic forgetting in continual instruction learning for LLMs through a switching mechanism for routing computations to parameter-efficient tuned models. We demonstrate the effectiveness of our method through experiments on continual instruction tuning of different natural language generation tasks.
