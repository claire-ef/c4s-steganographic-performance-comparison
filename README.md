## COMP90055 Research Project: A steganographic performance comparison of the C4S algorithm with selected SSIS algorithms

This repository contains the code for COMP90055 Research Project. Three Spread Spectrum Image Steganography (SSIS)
algorithms are implemented:
* ExtendedC4S.java [[1]](#1)
* KumarSS.m [[2]](#2)
* NaseemSS.java [[3]](#3)

The evaluation framework proposed by Eze et al. [[4]](#4) is used to evaluate and compare the three algorithms:
* code for computing PSNR/SSIM/BER can be found in Measurement.java
* biomarker extractions are implemented in featureGeneration.m
* biomarker related criteria are computed and SVM models are fit in biomarkers_and_SVM.ipynb
* attacks on watermarked images are performed in performAttacks.m

### References
<a id="1">[1]</a>
Peter U Eze, Udaya Parampalli, Robin J Evans, and Dongxi Liu.
Spread spectrum steganographic capacity improvement for medical image security in teleradiology.
In 2018 40th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), pages 1–4. IEEE, 2018.

<a id="1">[2]</a>
Basant Kumar, Harsh Vikram Singh, Surya Pal Singh, Anand Mohan, et al.
Secure spread-spectrum watermarking for telemedicine applications.
Journal of Information Security, 2(02):91, 2011.

<a id="1">[3]</a>
Muhammad Tahir Naseem, Ijaz Mansoor Qureshi, Muhammad Zeeshan Muzaffar, and Atta ur Rahman 0001.
Spread spectrum based invertible watermarking for medical images using RNS and Chaos. Int. Arab J. Inf. Technol., 13(2):223–231, 2016.

<a id="1">[4]</a>
Peter Eze, Udaya Parampalli, Robin Evans, and Dongxi Liu.
A new evaluation method for medical image information hiding techniques.
In 2020 42nd annual international conference of the IEEE engineering in Medicine & Biology Society (EMBC), pages 6119–6122. IEEE, 2020.
