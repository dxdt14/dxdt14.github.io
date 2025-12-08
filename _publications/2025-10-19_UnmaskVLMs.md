---
title: "Unmasking the functionality of the early layers in VLMs"
collection: publications
category: manuscripts
excerpt: 'Presented at the eXCV Workshop at ICCV 2025. Interpretability work on determining how vision is transformed in the early layers in VLMs. '
date: 2025-10-19
paperurl: 'https://excv-workshop.github.io/publication/unmasking-the-functionality-of-early-layers-in-vlms/'
citation: 'Hartman, M.*, Jayaraman, V.A.*, Choraria, M., Bhimaraju, A., & Varshney, L. R. (2025). Unmasking the
functionality of early layers in VLMs'
---

Recent work on analyzing the functionality of vision language models has observed that key multimodal processing occurs in the middle to late layers. This raises a natural question about the role of early layers, which is the central focus of our investigation. To explore this, we employ layer skipping as a more suitable alternative to the commonly used attention masking, motivated by our finding that masking vision tokens in early layers substantially degrades performance, whereas skipping the same layers does not. Using layer skipping, we find that vision tokens largely pass unaltered through the early layers of the language model, supporting the view that these layers primarily function as copying heads for visual tokens. This insight highlights opportunities to improve model efficiency by reducing redundant computation in the early stages.