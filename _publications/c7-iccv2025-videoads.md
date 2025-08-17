---
title: "VideoAds for Fast-Paced Video Understanding: Where Opensource Foundation Models Beat GPT-4o & Gemini-1.5 Pro"
collection: publications
category: conferences
permalink: /publication/iccv2025-videoads
# excerpt: 'MICCAI-AIPAD 2024'
# date: 2024-10
venue: 'ICCV 2025'
slidesurl: 'https://videoadsbenchmark.netlify.app/'
paperurl: 'https://arxiv.org/abs/2504.09282'
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

Advertisement videos serve as a rich and valuable source of purpose-driven information, encompassing high-quality visual, textual, and contextual cues designed to engage viewers. They are often more complex than general videos of similar duration due to their structured narratives and rapid scene transitions, posing significant challenges to multimodal large language models (MLLMs). In this work, we introduce VideoAds, the first dataset tailored for benchmarking the performance of MLLMs on advertisement videos. VideoAds comprises well-curated advertisement videos with complex temporal structures, accompanied by manually annotated diverse questions across three core tasks: visual finding, video summary, and visual reasoning. We propose a quantitative measure to compare VideoAds against existing benchmarks in terms of video complexity. Through extensive experiments, we find that Qwen2.5-VL-72B, an opensource MLLM, achieves 73.35% accuracy on VideoAds, outperforming GPT-4o (66.82%) and Gemini-1.5 Pro (69.66%); the two proprietary models especially fall behind the opensource model in video summarization and reasoning, but perform the best in visual finding. Notably, human experts easily achieve a remarkable accuracy of 94.27%. These results underscore the necessity of advancing MLLMs’ temporal modeling capabilities and highlight VideoAds as a potentially pivotal benchmark for future research in understanding video that requires high FPS sampling. The dataset and evaluation code will be publicly available at https://videoadsbenchmark.netlify.app.

<!-- ![aipad2024](/paper_figs/aipad2024.png) -->