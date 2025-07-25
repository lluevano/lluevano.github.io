---
title: "Identity-Preserving Aging and De-Aging of Faces in the StyleGAN Latent Space"
collection: publications
permalink: /publication/2025-09-08-ID-preserving-aging
excerpt: "Face aging or de-aging with generative AI has gained significant attention for its applications in such fields like forensics, security, and media. However, most state of the art methods rely on conditional Generative Adversarial Networks (GANs), Diffusion-based models, or Visual Language Models (VLMs) to age or de-age faces based on predefined age categories and conditioning via loss functions, fine-tuning, or text prompts. The reliance on such conditioning leads to complex training requirements, increased data needs, and challenges in generating consistent results. Additionally, identity preservation is rarely taken into account or evaluated on a single face recognition system without any control or guarantees on whether identity would be preserved in a generated aged/de-aged face. In this paper, we propose to synthesize aged and de-aged faces via editing latent space of StyleGAN2 using a simple support vector modeling of aging/de-aging direction and several feature selection approaches. By using two state-of-the-art face recognition systems, we empirically find the identity preserving subspace within the StyleGAN2 latent space, so that an apparent age of a given face can changed while preserving the identity. We then propose a simple yet practical formula for estimating the limits on aging/de-aging parameters that ensures identity preservation for a given input face. Using our method and estimated parameters we have generated a public dataset of synthetic faces at different ages that can be used for benchmarking cross-age face recognition, age assurance systems, or systems for detection of synthetic images. Our code and dataset are available at the project page https://www.idiap.ch/paper/agesynth/
"
date: 2025-09-08
venue: 'IEEE Joint Conference on Biometrics (IJCB) 2025'
paperurl: 'to appear'
citation: 'Luis S. Luevano, Pavel Korshunov, Sébastien Marcel. "Identity-Preserving Aging and De-Aging of Faces in the StyleGAN Latent Space". IEEE Joint Conference on Biometrics (IJCB) 2025.'
---
Face aging or de-aging with generative AI has gained significant attention for its applications in such fields like forensics, security, and media. However, most state of the art methods rely on conditional Generative Adversarial Networks (GANs), Diffusion-based models, or Visual Language Models (VLMs) to age or de-age faces based on predefined age categories and conditioning via loss functions, fine-tuning, or text prompts. The reliance on such conditioning leads to complex training requirements, increased data needs, and challenges in generating consistent results. Additionally, identity preservation is rarely taken into account or evaluated on a single face recognition system without any control or guarantees on whether identity would be preserved in a generated aged/de-aged face. In this paper, we propose to synthesize aged and de-aged faces via editing latent space of StyleGAN2 using a simple support vector modeling of aging/de-aging direction and several feature selection approaches. By using two state-of-the-art face recognition systems, we empirically find the identity preserving subspace within the StyleGAN2 latent space, so that an apparent age of a given face can changed while preserving the identity. We then propose a simple yet practical formula for estimating the limits on aging/de-aging parameters that ensures identity preservation for a given input face. Using our method and estimated parameters we have generated a public dataset of synthetic faces at different ages that can be used for benchmarking cross-age face recognition, age assurance systems, or systems for detection of synthetic images. Our code and dataset are available at the project page https://www.idiap.ch/paper/agesynth/

<div style="text-align: center"><img src="/images/publications/2025/teaser_agesynth.png" width="400px" /></div>

[Paper](/files/paper.ijcb2025.agesynth.pdf) <br>
[Poster](/files/Poster_EAB_Citer_Idiap2025_Luevano.pdf) <br>
[Code and dataset](https://www.idiap.ch/paper/agesynth/)

<!-- Recommended citation: Yoanna Martínez-Díaz, Heydi Méndez-Vázquez, Luis S. Luevano, Miguel Gonzalez-Mendoza; Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops, 2023, pp. 6391-6401 -->

Latex citation:
~~~ BibTex
@InProceedings{Luevano_2025_Agesynth,
    author    = {Luevano, Luis S. and Korshunov, Pavel, and Marcel, S\'{e}bastien},
    title     = {Identity-Preserving Aging and De-Aging of Faces in the StyleGAN Latent Space},
    booktitle = {IEEE Joint Conference on Biometrics (IJCB) 2025},
    month     = {September},
    year      = {2025},
}
~~~
