---
title: "Utilizing CNNs for Cryptanalysis of Selective Biometric Face Sample Encryption"
collection: publications
permalink: /publication/2022-08-21-CNNs-for-Cryptanalysis
excerpt: 'When storing face biometric samples in accordance with ISO/IEC 19794 as JPEG2000 encoded images, it is necessary to encrypt them for the sake of users’ privacy. Literature suggests selective encryption of JPEG2000 images as fast and efficient method for encryption, the trade-off is that some information is left in plaintext. This could be used by an attacker, in case the encrypted biometric samples are leaked. In this work, we will attempt to utilize a convolutional neural network to perform cryptanalysis of the encryption scheme. That is, we want to assess if there is any information left in plaintext in the selectively encrypted face images which can be used to identify the person. The chosen approach is to train CNNs for biometric face recognition not only with plaintext face samples but additionally conduct a refinement training with partially encrypted data. If this system can successfully utilize encrypted face samples for biometric matching, we can show that the information left in encrypted biometric face samples is information actually usable for biometric recognition.The method works and we can show that a supposedly secure biometric sample still contains identifying information on average over the whole database.'
date: 2022-08-21
venue: '26th International Conference on Pattern Recognition (ICPR) 2022'
paperurl: 'https://doi.org/10.1109/ICPR56361.2022.9956664'
citation: 'H. Hofbauer, Y. Martínez-Díaz, L. S. Luevano, H. Méndez-Vázquez and A. Uhl, "Utilizing CNNs for Cryptanalysis of Selective Biometric Face Sample Encryption," <em>2022 26th International Conference on Pattern Recognition (ICPR)<em>, Montreal, QC, Canada, 2022, pp. 892-899, doi: 10.1109/ICPR56361.2022.9956664.'
---
When storing face biometric samples in accordance with ISO/IEC 19794 as JPEG2000 encoded images, it is necessary to encrypt them for the sake of users’ privacy. Literature suggests selective encryption of JPEG2000 images as fast and efficient method for encryption, the trade-off is that some information is left in plaintext. This could be used by an attacker, in case the encrypted biometric samples are leaked. In this work, we will attempt to utilize a convolutional neural network to perform cryptanalysis of the encryption scheme. That is, we want to assess if there is any information left in plaintext in the selectively encrypted face images which can be used to identify the person. The chosen approach is to train CNNs for biometric face recognition not only with plaintext face samples but additionally conduct a refinement training with partially encrypted data. If this system can successfully utilize encrypted face samples for biometric matching, we can show that the information left in encrypted biometric face samples is information actually usable for biometric recognition.The method works and we can show that a supposedly secure biometric sample still contains identifying information on average over the whole database.

[Download paper here](https://doi.org/10.1109/ICPR56361.2022.9956664)

Recommended citation: H. Hofbauer, Y. Martínez-Díaz, L. S. Luevano, H. Méndez-Vázquez and A. Uhl, "Utilizing CNNs for Cryptanalysis of Selective Biometric Face Sample Encryption," <em>2022 26th International Conference on Pattern Recognition (ICPR)<em>, Montreal, QC, Canada, 2022, pp. 892-899, doi: 10.1109/ICPR56361.2022.9956664.

Latex:
<pre>
@INPROCEEDINGS{Hofbauer-CNN-Cryptanalysis-ICPR-2022,
  author={Hofbauer, Heinz and Martínez-Díaz, Yoanna and Luevano, Luis Santiago and Méndez-Vázquez, Heydi and Uhl, Andreas},
  booktitle={2022 26th International Conference on Pattern Recognition (ICPR)}, 
  title={Utilizing CNNs for Cryptanalysis of Selective Biometric Face Sample Encryption}, 
  year={2022},
  volume={},
  number={},
  pages={892-899},
  doi={10.1109/ICPR56361.2022.9956664}}
</pre>
