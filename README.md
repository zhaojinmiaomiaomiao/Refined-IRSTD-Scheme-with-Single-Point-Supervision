## The code for paper "Refined Infrared Small Target Detection Scheme with Single-Point Supervision" [[Paper/arXiv](https://www.arxiv.org/abs/2408.02773)]  

**The proposed scheme won the *2nd prize* in the "ICPR 2024 Resource-Limited Infrared Small Target Detection Challenge Track 1: Weakly Supervised Infrared Small Target Detection"**  

**The scheme of our another *2nd prize* in the ICPR 2024 Resource-Limited Infrared Small Target Detection Challenge Track 2: Lightweight Infrared Small Target Detection. see ([[LR-Net](https://arxiv.org/abs/2408.02780)] [[code](https://github.com/YuChuang1205/LR-Net)])**

This code is based on Label Evolution with Single Point Supervision (LESPS) ([[link](https://github.com/XinyiYing/LESPS?tab=readme-ov-file)]) by Dr. Xinyi Ying. Thanks to the previous work.

In this code, we have integrated multiple networks (**ACM**([[paper](https://ieeexplore.ieee.org/document/9423171)]), **ALCNet**([[paper](https://ieeexplore.ieee.org/document/9314219)]), **MLCL-Net**([[paper](https://doi.org/10.1016/j.infrared.2022.104107)]), **ALCL-Net**([[paper](https://ieeexplore.ieee.org/document/9785618)]), **DNA-Net**([[paper](https://ieeexplore.ieee.org/document/9864119)]), **GGL-Net**([[paper](https://ieeexplore.ieee.org/abstract/document/10230271)])) for use. For MLCL-Net, there are two versions in the code: MLCL-Net (small) and MLCL-Net (base). For details, see the description in the corresponding model code file. It is worth noting that we use MLCL-Net (small) in this paper.

For the data set creation, you can use "centroid_anno.m" and "coarse_anno.m". For details, please refer to the details in LESPS ([[link](https://github.com/XinyiYing/LESPS?tab=readme-ov-file)])

It is worth mentioning that GGL-Net ([[paper](https://ieeexplore.ieee.org/abstract/document/10230271)]) has extremely excellent performance in this task. For specific performance comparisons of each network, please refer to the paper [[Paper/arXiv](https://www.arxiv.org/abs/2408.02773)]. 

If you have any questions, please feel free to ask. I will reply in time on github.  


### Other link
1. My homepage: [[YuChuang](https://github.com/YuChuang1205)]
