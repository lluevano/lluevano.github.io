---
title: "Improving Low-Resolution Face Recognition under Limited Data: How Synthetic Data Generation Can Close the Domain Gap"
collection: publications
permalink: /publication/2026-09-01-Synthetic-LRFR
excerpt: "Face Recognition (FR) systems in surveillance settings often encounter Low Resolution (LR) faces, those whose face region falls below the standard 112 × 112 input size. While labelled High Resolution (HR) training data is abundant, labelled native-LR data, and above all paired native-LR/HR data, is scarce. One workaround is to synthesize LR data from the available HR faces, but how much synthesis effort is repaid in recognition accuracy remains unclear. We present a study of simple synthetic generation strategies for a compact, edge device-oriented face recognition system, spanning interpolation-based degradation, knowledge distillation, a Prepended Domain Transformer (PDT), Real-ESRGAN-style degradation, and a learned Super Resolution (SR) front-end with an identity-aware loss. We evaluate these strategies on synthetic cross-resolution face benchmarks (LFW, CFP-FP, AgeDB-30) and on TinyFace, a real-world native LR dataset, and expose a synthetic–real gap: the degradation setting that is optimal on synthetic benchmarks is not the one that is optimal on real LR. We find that more synthesis effort does not help monotonically: the learned SR front-end does not surpass a direct feed of the aligned LR image into a strong backbone, while simple interpolation augmentation of a compact backbone is the only synthesis that improves over its own baseline. We conclude that generative methods for LR face recognition must be validated on real LR and against a direct-feed baseline, and release our pipeline at https://idiap.ch/paper/synth-lrfr.
"
date: 2026-09-01
venue: 'IEEE International Joint Conference on Biometrics (IJCB) 2026, Focus Session on Generative AI for Fair and Secure Biometrics under Limited Data'
citation: 'Luis S. Luevano, Ünsal Öztürk, Hatef Otroshi Shahreza, Anjith George, Sébastien Marcel. "Improving Low-Resolution Face Recognition under Limited Data: How Synthetic Data Generation Can Close the Domain Gap". IEEE International Joint Conference on Biometrics (IJCB) 2026, Focus Session on Generative AI for Fair and Secure Biometrics under Limited Data.'
---
Face Recognition (FR) systems in surveillance settings often encounter Low Resolution (LR) faces, those whose face region falls below the standard 112 × 112 input size. While labelled High Resolution (HR) training data is abundant, labelled native-LR data, and above all paired native-LR/HR data, is scarce. One workaround is to synthesize LR data from the available HR faces, but how much synthesis effort is repaid in recognition accuracy remains unclear. We present a study of simple synthetic generation strategies for a compact, edge device-oriented face recognition system, spanning interpolation-based degradation, knowledge distillation, a Prepended Domain Transformer (PDT), Real-ESRGAN-style degradation, and a learned Super Resolution (SR) front-end with an identity-aware loss. We evaluate these strategies on synthetic cross-resolution face benchmarks (LFW, CFP-FP, AgeDB-30) and on TinyFace, a real-world native LR dataset, and expose a synthetic–real gap: the degradation setting that is optimal on synthetic benchmarks is not the one that is optimal on real LR. We find that more synthesis effort does not help monotonically: the learned SR front-end does not surpass a direct feed of the aligned LR image into a strong backbone, while simple interpolation augmentation of a compact backbone is the only synthesis that improves over its own baseline. We conclude that generative methods for LR face recognition must be validated on real LR and against a direct-feed baseline, and release our pipeline at [https://idiap.ch/paper/synth-lrfr](https://idiap.ch/paper/synth-lrfr).

Our main conclusions are:
- The degradation setting that is optimal on synthetic benchmarks is not the one that is optimal on real LR: 28 ↓c/↑a is best across the synthetic benchmarks yet is the worst configuration on TinyFace, where the milder 56 px setting wins.
- Synthesis effort does not pay off monotonically; on a retrainable compact backbone the cheapest interpolation augmentation beats both Real-ESRGAN-style degradation and a learned SR front-end.
- A learned, identity-aware super-resolution front-end never beats simply feeding a strong frozen backbone the aligned LR image, so a direct-feed baseline should be reported before any restoration or translation pipeline is claimed to help.
- The average-accuracy gains from LR-aware synthesis do not reduce demographic bias: the FMR disparity on RFW shows no consistent improvement.

Accepted at the [Focus Session on Generative AI for Fair and Secure Biometrics under Limited Data](https://ijcb2026.ieee-biometrics.org/generative-ai-for-fair-and-secure-biometrics-under-limited-data/) at IJCB 2026. Camera-ready and project page coming soon.

[Project page](https://idiap.ch/paper/synth-lrfr) <br>
[Paper on arXiv](https://arxiv.org/abs/2608.06580)
[Code details](https://lluevano.github.io/portfolio/2026-09-01-synthlrfr_code/)

Latex citation:
~~~ BibTex
@inproceedings{luevano2026synthlrfr,
  title={Improving Low-Resolution Face Recognition under Limited Data: How Synthetic Data Generation Can Close the Domain Gap},
  author={Luevano, Luis S. and {\"O}zt{\"u}rk, {\"U}nsal and Otroshi Shahreza, Hatef and George, Anjith and Marcel, S{\'e}bastien},
  booktitle={2026 IEEE International Joint Conference on Biometrics (IJCB)},
  year={2026},
  note={Accepted at the 2026 IJCB Focus Session "Generative AI for Fair and Secure Biometrics under Limited Data"}
}
~~~
