---
title: "Hiding in Plain Sight: Detectability-Aware Antidistillation of Reasoning Models"
collection: publications
category: preprints
authors: 'M. Hartman<sup>*</sup>, <strong>V. A. Jayaraman</strong><sup>*</sup>, M. Choraria, and L. R. Varshney'
venue_status: 'Under review at NeurIPS 2026'
excerpt: 'An extended version of our [TAIGR workshop paper](/publications/2026-05-4_ICML_Antidistill/). We formalize detectability in antidistillation and target a sparse set of influential reasoning sentences to hinder student learning while preserving trace coherence.'
date: 2026-09-04
paperurl: 'https://arxiv.org/abs/2604.23238'
citation: 'Hartman, M.*, Jayaraman, V.A.*, Choraria, M., Varshney, L.R. (2026). Hiding in Plain Sight: Detectability-Aware Antidistillation of Reasoning Models'
---

Distillation via sampling reasoning traces exposes closed-source frontier models to adversarial third parties who can bypass their guardrails and misappropriate their capabilities. Antidistillation methods aim to address this by poisoning reasoning traces to hinder student model learning while preserving teacher performance. However, current methods overlook detectability, both semantic and syntactic, which erodes trust in the teacher's outputs and signals the defense's presence to adversaries. We address this gap by formulating antidistillation as a Stackelberg game whose constraint set explicitly encodes detectability, and show that perturbing sparingly offers an effective, less detectable alternative to poisoning the full trace. Drawing on mechanistic interpretability, we identify thought anchors, sentences with disproportionate counterfactual influence on model outputs, as a principled sparse target: critical to reasoning yet minimally detectable. We instantiate this in TraceGuard, a training-free, black-box proof-of-concept that locates thought anchors via branching-token detection and poisons them to degrade student distillation while preserving trace coherence.
