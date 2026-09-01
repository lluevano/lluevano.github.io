---
title: "Code release for the paper 'Improving Low-Resolution Face Recognition under Limited Data: How Synthetic Data Generation Can Close the Domain Gap'"
excerpt: "This is the code repository release for the paper 'Improving Low-Resolution Face Recognition under Limited Data: How Synthetic Data Generation Can Close the Domain Gap' accepted at the IEEE International Joint Conference on Biometrics (IJCB) 2026. <br/> [Link to Repository](https://gitlab.idiap.ch/biometric/code.ijcb2026.synth-lrfr) <br/><img src='/images/publications/2026/teaser_synth_lrfr.png' width='200px'>"
collection: portfolio
---

This is the code repository release for the paper "Improving Low-Resolution Face Recognition under Limited Data: How Synthetic Data Generation Can Close the Domain Gap" accepted at the Focus Session on Generative AI for Fair and Secure Biometrics under Limited Data at the IEEE International Joint Conference on Biometrics (IJCB) 2026.

The repository implements and compares five adaptation strategies for low-resolution face recognition on a compact, edge-oriented backbone (EdgeFace-S), spanning three levels of synthesis effort: interpolation-based degradation, knowledge distillation from a frozen high-resolution teacher, a Prepended Domain Transformer (PDT), a native 32 px stem trained on Real-ESRGAN-style degraded data, and a learned super-resolution front-end trained with an identity-aware loss. It also includes the data synthesis pipeline that builds the degraded training records and verification sets, and the full evaluation suite: the synthetic cross-resolution benchmarks (LFW, CFP-FP, AgeDB-30) in both HR→LR and LR→LR modalities, IJB-C, the RFW fairness protocol, and identification on TinyFace, the real-world native low-resolution dataset that exposes the synthetic–real gap. TinyFace alignment is provided under both padded-crop and differentiable face aligner (DFA) pipelines, since the choice of aligner moves absolute accuracy by a large margin.

See more at: <br>
[Link to Repository](https://github.com/idiap/Synthetic-Data-Generation-for-Low-Resolution-Face-Recognition) <br>
[Link to the project page](https://www.idiap.ch/paper/synth-lrfr/) <br>
[Link to the paper on arXiv](https://arxiv.org/abs/2608.06580) <br>
[Link to our publication details](https://lluevano.github.io/publication/2026-09-01-Synthetic-LRFR)

<img src='/images/publications/2026/teaser_synth_lrfr.png'>
