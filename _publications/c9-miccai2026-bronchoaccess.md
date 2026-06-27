---
title: "Anatomy-Aware Prediction of Bronchoscopic Accessibility from 3D CT"
collection: publications
category: conferences
permalink: /publication/miccai2026-bronchoaccess
# excerpt: 'MICCAI-AIPAD 2024'
# date: 2024-10
venue: 'MICCAI 2026'
slidesurl: 'https://nubagcilab.github.io/BronchoAccess/'
paperurl: ''
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

Pre-operative planning for bronchoscopy is critical for the diagnosis of lung lesions. Current accessibility assessment relies on subjective manual inspection of CT scans, which is time-consuming and prone to inter-observer variability. In this paper, we formalize bronchoscopy accessibility prediction as a novel supervised learning task and present the first end-to-end framework to address it. We propose an Anatomy-Aware Mixture-of-Experts (MoE) model that integrates specialized modules: a CT Expert for local morphological features, a Lobe Expert for anatomical priors, and a Path Geometry Expert that encodes the sequential constraints of the bronchial tree. To support this task, we curated the first clinical dataset of 438 cases with pre-operative CT scans and documented procedural outcomes. Experimental results demonstrate that our method achieves an AUROC of 0.8052, significantly outperforming both state-of-the-art baselines and experienced human experts. This work establishes a new benchmark for computer-aided interventional planning in pulmonary medicine. Our data and code will be publicly available at https://nubagcilab.github.io/BronchoAccess/.

![miccai2026](/paper_figs/miccai2026.png)