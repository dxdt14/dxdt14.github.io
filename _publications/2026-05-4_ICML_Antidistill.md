---
title: "Protecting the Trace: A Principled Black-Box Approach Against Distillation Attacks"
collection: publications
category: workshops
authors: 'M. Hartman<sup>*</sup>, <strong>V. A. Jayaraman</strong><sup>*</sup>, M. Choraria, and L. R. Varshney'
venue_status: 'TAIGR Workshop at ICML 2026'
excerpt: 'The workshop version of our antidistillation work. We formulate the problem as a Stackelberg game and introduce TraceGuard, a black-box defense for reasoning traces. Extended as [Hiding in Plain Sight](/publications/2026-09-4_NeurIPS_Antidistill/).'
date: 2026-05-04
paperurl: 'https://arxiv.org/abs/2604.23238v1'
citation: 'Hartman, M.*, Jayaraman, V.A.*, Choraria, M., Varshney, L.R. (2026). Protecting the Trace: A Principled Black-Box Approach Against Distillation Attacks'
---

Frontier models push the boundaries of what is learnable at extreme computational costs, yet distillation via sampling reasoning traces exposes closed-source frontier models to adversarial third parties who can bypass their guardrails and misappropriate their capabilities, raising safety, security, and intellectual privacy concerns. To address this, there is growing interest in building antidistillation methods, which aim to poison reasoning traces to hinder downstream student model learning while maintaining teacher performance. However, current techniques lack theoretical grounding, requiring either heavy fine-tuning or access to student model proxies for gradient based attacks, and often lead to a significant teacher performance degradation. In this work, we present a theoretical formulation of antidistillation as a Stackelberg game, grounding a problem that has so far largely been approached heuristically. Guided by the desired design properties our formulation reveals, we propose \texttt{TraceGuard}, an efficient, post-generation black-box method to poison sentences with high importance for teacher reasoning. Our work offers a scalable solution to share model insights safely, ensuring that the advancement of reasoning capabilities does not come at the cost of intellectual privacy or AI safety alignment.
