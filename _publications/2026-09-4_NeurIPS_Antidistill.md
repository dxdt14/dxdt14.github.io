---
title: "Hiding in Plain Sight: Detectability-Aware Antidistillation of Reasoning Models"
collection: publications
category: manuscripts
excerpt: 'Under Review for NeurIPS 2026. We propose a framework for antidistillation that formalizes detectability, motivates targeting a sparse set of important reasoning sentences, and validates the approach with a method that removes thought anchors to degrade student distillation.'
date: 2026-09-04
paperurl: 'https://arxiv.org/abs/2604.23238'
citation: 'Hartman, M.*, Jayaraman, V.A.*, Choraria, M., Varshney, L.R. (2026). Hiding in Plain Sight: Detectability-AwareAntidistillation of Reasoning Models'
---

Distillation via sampling reasoning traces exposes closed-source frontier models to adversarial third parties who can bypass their guardrails and misappropriate their capabilities. Antidistillation methods aim to address this by poisoning reasoning traces to hinder student model learning while preserving teacher performance. However, current methods overlook detectability, both semantic and syntactic, which erodes trust in the teacher's outputs and signals the defense's presence to adversaries. We address this gap by formulating antidistillation as a Stackelberg game whose constraint set explicitly encodes detectability, and show that perturbing sparingly offers an effective, less detectable alternative to poisoning the full trace. Drawing on mechanistic interpretability, we identify thought anchors, sentences with disproportionate counterfactual influence on model outputs, as a principled sparse target: critical to reasoning yet minimally detectable. We instantiate this in TraceGuard, a training-free, black-box proof-of-concept that locates thought anchors via branching-token detection and poisons them to degrade student distillation while preserving trace coherence.

