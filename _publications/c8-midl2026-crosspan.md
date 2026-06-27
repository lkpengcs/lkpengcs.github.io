---
title: "CrossPan: A Comprehensive Benchmark for Cross-Sequence Pancreas MRI Segmentation and Generalization"
collection: publications
category: conferences
permalink: /publication/midl2026-crosspan
# excerpt: 'MICCAI-AIPAD 2024'
# date: 2024-10
venue: 'MIDL 2026'
slidesurl: 'https://crosspan.netlify.app/'
paperurl: 'https://openreview.net/pdf?id=Ma4ffI5XqT'
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

Pancreas MRI segmentation remains challenging due to heterogeneous acquisition protocols and the limited availability of annotated multi-sequence data. While prior studies have examined cross-center robustness, the impact of variations across MRI sequences has received far less attention. We present CrossPan, a comprehensive empirical benchmark for evaluating segmentation robustness under heterogeneous abdominal MRI sequences. The benchmark comprises 1386 3D scans from eight institutions across three routinely acquired sequences (T1-weighted, T2-weighted, and Out-of-Phase). Across five tasks, we find that: (i) cross-sequence shifts constitute a substantially more severe challenge than cross-center variability; (ii) state-of-the-art DG methods show limited effectiveness in bridging the gap, while zero-shot foundation models exhibit heterogeneous robustness; and (iii) semi-supervised learning offers moderate gains at mid-range label ratios but remains unstable under extreme scarcity and exhibits strong sequence dependence. These results highlight the fundamental difficulty of cross-sequence generalization in abdominal MRI and position CrossPan as a rigorous platform for advancing robust and clinically reliable pancreas segmentation. Dataset and code are available at https://crosspan.netlify.app/.

<!-- ![aipad2024](/paper_figs/aipad2024.png) -->