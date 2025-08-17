---
title: "TAGS: 3D Tumor-Adaptive Guidance for SAM"
collection: publications
category: conferences
permalink: /publication/iccv2025-tags
# excerpt: 'MICCAI-AIPAD 2024'
# date: 2024-10
venue: 'ICCV-APAH 2025'
slidesurl: 'https://github.com/sirileeee/TAGS'
paperurl: 'https://arxiv.org/abs/2505.17096'
# citation: 
# ```
# @article{peng2024optimizing,
#   title={Optimizing Synthetic Data for Enhanced Pancreatic Tumor Segmentation},
#   author={Peng, Linkai and Zhang, Zheyuan and Durak, Gorkem and Miller, Frank H and Medetalibeyoglu, Alpay and Wallace, Michael B and Bagci, Ulas},
#   journal={arXiv preprint arXiv:2407.19284},
#   year={2024}
# }
# ```
---

Foundation models (FMs) such as CLIP and SAM have recently shown great promise in image segmentation tasks, yet their adaptation to 3D medical imaging—particularly for pathology detection/segmentation—remains underexplored. A critical challenge arises from the domain gap between natural images and medical volumes: existing FMs, pre-trained on 2D data, struggle to capture 3D anatomical context, limiting their utility in clinical applications like tumor segmentation. To address this, we propose an adaptation framework called TAGS: Tumor Adaptive Guidance for SAM, which unlocks 2D FMs for 3D medical tasks through multi-prompt fusion. By preserving most of the pre-trained weights, our approach enhances SAM’s spatial feature extraction using CLIP’s semantic insights and anatomy-specific prompts. Extensive experiments on three open-source tumor segmentation datasets prove that our model surpasses the state-of-the-art medical image segmentation models (+46.88% over nnUNet), interactive segmentation frameworks, and other established medical FMs, including SAM-Med2D, SAM-Med3D, SegVol, Universal, 3D-Adapter, and SAM-B (at least +13% over them). This highlights the robustness and adaptability of our proposed framework across diverse medical segmentation tasks. Our code and model are available at: https://github.com/sirileeee/TAGS.

<!-- ![aipad2024](/paper_figs/aipad2024.png) --> -->