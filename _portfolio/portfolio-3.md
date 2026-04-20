---
title: "Mechanistic Interpretability via SAEs for French Technical Corpora"
excerpt: "A Proof of Concept (PoC) implementing a 'Frozen Core' Matryoshka Sparse Autoencoder to extract causal features from LLMs on scarce French data."
collection: portfolio
---

As part of my research internship at EDF R&D, I developed a resource-efficient Matryoshka Sparse Autoencoder (SAE) to tackle the challenge of domain adaptation in mechanistic interpretability.

**Key Highlights:**
* Implementation of a Matryoshka architecture with a frozen pre-trained core to prevent catastrophic forgetting.
* Tracking of Fraction of Variance Explained (FVE) to measure reconstruction fidelity.
* Identification of BPE tokenization bottlenecks and routing interference during inference.

[View the complete Jupyter Notebook code here](https://github.com/gregoirepelletier/gregoirepelletier.github.io/blob/master/assets/notebooks/POC_Matryoshka_SAE_French.ipynb)
