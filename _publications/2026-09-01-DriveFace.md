---
title: "DriveFace: A Cross-Spectral Through-Glass Face Dataset for On-the-Move Vehicular Border Control"
collection: publications
permalink: /publication/2026-09-01-DriveFace
excerpt: "The continuous growth in cross-border mobility places increasing pressure on existing border control infrastructures, motivating on-the-move biometric authentication, in which travellers are identified directly inside their vehicles at checkpoints. Face recognition is well-suited to this setting, as it can be acquired passively and at a distance. Its development, however, is hindered by the lack of representative datasets: existing benchmarks are collected in controlled environments and do not capture the challenges inherent to vehicular acquisition, including motion blur, variable illumination, occlusions, and cross-spectral enrollment. To address this gap, we introduce DriveFace, a dataset for on-the-move face recognition in border-control scenarios, comprising NIR vehicle-crossing videos paired with smartphone-based pre-enrollment data. Baseline evaluations with state-of-the-art models show clear performance limitations under these realistic conditions, highlighting the need for dedicated methods to advance the field.
"
date: 2026-09-01
venue: 'IEEE International Joint Conference on Biometrics (IJCB) 2026'
paperurl: 'https://publications.idiap.ch/attachments/papers/2026/George_IJCB2026_2026.pdf'
citation: 'Anjith George, Luis S. Luevano, Alain Komaty, Zeina Al Amine, Vidit Vidit, Sébastien Marcel. "DriveFace: A Cross-Spectral Through-Glass Face Dataset for On-the-Move Vehicular Border Control". IEEE International Joint Conference on Biometrics (IJCB) 2026.'
---
The continuous growth in cross-border mobility places increasing pressure on existing border control infrastructures, motivating *on-the-move* biometric authentication, in which travellers are identified directly inside their vehicles at checkpoints. Face recognition is well-suited to this setting, as it can be acquired passively and at a distance. Its development, however, is hindered by the lack of representative datasets: existing benchmarks are collected in controlled environments and do not capture the challenges inherent to vehicular acquisition, including motion blur, variable illumination, occlusions, and cross-spectral enrollment. To address this gap, we introduce **DriveFace**, a dataset for on-the-move face recognition in border-control scenarios, comprising NIR vehicle-crossing videos paired with smartphone-based pre-enrollment data. Baseline evaluations with state-of-the-art models show clear performance limitations under these realistic conditions, highlighting the need for dedicated methods to advance the field.

<div style="text-align: center"><img src="/images/publications/2026/teaser_driveface.jpg" width="400px" /></div>

Highlights:
- 70 consenting subjects captured over two sessions approximately two months apart, pairing visible-spectrum smartphone pre-enrollment with in-vehicle NIR probes.
- Cross-spectral, through-glass acquisition: RGB references matched against NIR probes captured through automotive windows at varying tint and viewing angles, under stationary and moving conditions.
- DriveFace-PAD presentation-attack subset with print, replay, and mask attacks under multiple tint and illumination levels.
- Rich metadata (tint level, illumination, head pose, vehicle speed) and standardized FR and PAD protocols with strong baseline results.

[Paper](https://publications.idiap.ch/attachments/papers/2026/George_IJCB2026_2026.pdf) <br>
[arXiv](https://arxiv.org/pdf/2607.13515) <br>
[Project page](https://www.idiap.ch/paper/driveface/) <br>
[Code](https://github.com/idiap/DriveFace) <br>
[Dataset](https://www.idiap.ch/en/scientific-research/data/driveface)

Latex citation:
~~~ BibTex
@inproceedings{george2026driveface,
  title={DriveFace: A Cross-Spectral Through-Glass Face Dataset for On-the-Move Vehicular Border Control},
  author={George, Anjith and Luevano, Luis S and Komaty, Alain and Al Amine, Zeina and Vidit, Vidit and Marcel, S\'ebastien},
  booktitle={2026 IEEE International Joint Conference on Biometrics (IJCB)},
  year={2026},
}
~~~
