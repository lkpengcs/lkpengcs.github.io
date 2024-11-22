---
title: "Optimizing Synthetic Data for Enhanced Pancreatic Tumor Segmentation"
collection: publications
category: conferences
permalink: /publication/miccai-aipad2024
# excerpt: 'MICCAI-AIPAD 2024'
# date: 2024-10
venue: 'MICCAI-AIPAD 2024'
slidesurl: 'https://github.com/lkpengcs/SynTumorAnalyzer'
paperurl: 'https://arxiv.org/abs/2407.19284'
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

Pancreatic cancer remains one of the leading causes of cancerrelated mortality worldwide. Precise segmentation of pancreatic tumors from medical images is a bottleneck for effective clinical decision-making. However, achieving a high accuracy is often limited by the small size and availability of real patient data for training deep learning models. Recent approaches have employed synthetic data generation to augment training datasets. While promising, these methods may not yet meet the performance benchmarks required for real-world clinical use. This study critically evaluates the limitations of existing generative-AI based frameworks for pancreatic tumor segmentation. We conduct a series of experiments to investigate the impact of synthetic tumor size and boundary definition precision on model performance. Our findings demonstrate that: (1) strategically selecting a combination of synthetic tumor sizes is crucial for optimal segmentation outcomes, and (2) generating synthetic tumors with precise boundaries significantly improves model accuracy. These insights highlight the importance of utilizing refined synthetic data augmentation for enhancing the clinical utility of segmentation models in pancreatic cancer decision making including diagnosis, prognosis, and treatment plans.

![aipad2024](/paper_figs/aipad2024.png)