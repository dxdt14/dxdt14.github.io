---
title: "Information-Theoretic Analysis of Knowledge Distillation"
collection: publications
category: theses
authors: '<strong>Vidhata Jayaraman</strong>'
venue_status: 'Senior Thesis · University of Illinois Urbana-Champaign, 2026'
advisor: '[Lav R. Varshney](https://varshney.csl.illinois.edu), [R. Srikant](https://sites.google.com/a/illinois.edu/srikant)'
excerpt: 'An information-theoretic study of the fundamental limits of knowledge distillation, including its interpretation as compression, performance limits for student models, and the formulation of antidistillation.'
paperurl: '/files/undergrad_thesis.pdf'
paper_label: 'Thesis PDF'
citation: 'Jayaraman, V. A. (2026). Information-Theoretic Analysis of Knowledge Distillation. Senior thesis, University of Illinois Urbana-Champaign.'
---

Knowledge Distillation (KD) has emerged as a cornerstone technique for transferring the learned representations of high-capacity "teacher" models to more efficient "student" architectures. While the empirical efficacy of KD is well-documented, a rigorous theoretical characterization of its underlying principles remains nascent. This thesis adopts an information-theoretic framework to investigate the fundamental limits of knowledge distillation, with a particular eye towards the compression of Large Language Model (LLM) architectures. By leveraging Rate-Distortion theory, we characterize the information-theoretic optimality of KD as a compression mechanism and establish achievability results for simple model classes. We further supplement this with analysis on performance limits of student models when trained via KD by leveraging techniques from learning theory. Finally, we introduce and formalize the concept of "antidistillation"---the strategic prevention of knowledge transfer--- and provide both a theoretical formulation and practical methodologies for its implementation.
