---
title: "Fargo: A joint framework for faz and rv segmentation from octa images"
collection: publications
category: conferences
permalink: /publication/miccai-omia2021
# excerpt: 'MICCAI-OMIA 2021'
# date: 2021-09
venue: 'MICCAI-OMIA 2021'
slidesurl: 'https://github.com/lkpengcs/FARGO'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-87000-3_5'
# citation: 
# ```
# @inproceedings{peng2021fargo,
#   title={Fargo: A joint framework for faz and rv segmentation from octa images},
#   author={Peng, Linkai and Lin, Li and Cheng, Pujin and Wang, Zhonghua and Tang, Xiaoying},
#   booktitle={Ophthalmic Medical Image Analysis: 8th International Workshop, OMIA 2021, Held in Conjunction with MICCAI 2021, Strasbourg, France, September 27, 2021, Proceedings 8},
#   pages={42--51},
#   year={2021},
#   organization={Springer}
# }
# ```
---

Optical coherence tomography angiography (OCTA) is a recent advance in ophthalmic imaging, which provides detailed visualization of two important anatomical landmarks, namely foveal avascular zone (FAZ) and retinal vessels (RV). Studies have shown that both FAZ and RV play significant roles in the diagnoses of various eye-related diseases. Therefore, accurate segmentation of FAZ and RV from OCTA images is highly in need. However, due to complicated microstructures and inhomogeneous image quality, there is still room for improvement in existing methods. In this paper, we propose a novel and efficient deep learning framework containing two subnetworks for simultaneously segmenting FAZ and RV from en-face OCTA images, named FARGO. For FAZ, we use RV segmentation as an auxiliary task, which may provide supplementary information especially for low-contrast and low-quality OCTA images. A ResNeSt based encoder with split attention and ImageNet pretraining is employed for FAZ segmentation. For RV, we introduce a coarse-to-fine cascaded network composed of a main segmentation model and several small ones for progressive refining. Spatial attention and channel attention modules are utilized for adaptively integrating local features with global dependencies. Through extensive experiments, FARGO is found to yield outstanding segmentation results for both FAZ and RV on the OCTA-500 dataset, performing even better than methods that utilize 3D OCTA volume as an extra input.

![omia2021](/paper_figs/omia2021.png)