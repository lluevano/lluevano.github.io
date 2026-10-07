---
title: "Improving Low-Resolution Face Recognition under Limited Data: How Synthetic Data Generation Can Close the Domain Gap"
collection: talks
type: "Oral presentation (15 min)"
permalink: /talks/2026-09-01-IJCB-2026-Synthetic-LRFR
venue: "IJCB 2026 Focus Session on Generative AI for Fair and Secure Biometrics under Limited Data"
date: 2026-09-01
location: "Rome, Italy"
---

Fifteen-minute oral presentation in the Focus Session on Generative AI for Fair and Secure Biometrics under Limited Data, plus a poster.

Surveillance face recognition often has to match faces of only 16–32 pixels against high-resolution galleries, and paired low/high-resolution training data is scarce. We studied synthetic low-resolution data generation for a compact face recognition model (EdgeFace-S) at three levels of effort: interpolation, Real-ESRGAN-style degradation, and a learned identity-aware super-resolution front-end. Main findings:

- The degradation that is best on synthetic benchmarks is the worst on real low-resolution faces (TinyFace).
- More synthesis effort does not pay off monotonically: simple interpolation augmentation beats the more complex options on the compact model.
- Feeding the aligned low-resolution face directly to a strong backbone is a hard baseline that the super-resolution pipeline does not beat.
- Accuracy gains do not reduce demographic bias on RFW.

Authors: Luis S. Luevano, Ünsal Öztürk, Hatef Otroshi Shahreza, Anjith George, Sébastien Marcel.

[Poster](/files/poster.ijcb2026.synth-lrfr.pdf) <br>
[Paper page](/publication/2026-09-01-Synthetic-LRFR) <br>
[Project page and code](https://idiap.ch/paper/synth-lrfr)
