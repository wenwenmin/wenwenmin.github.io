---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

You can also find my articles on [My Google Scholar Profile](https://scholar.google.com/citations?user=0Uy0GnoAAAAJ&hl=en)

\*corresponding author

# 课题组软件列表

## [STMask](https://github.com/donghaifang/STMask/tree/main)
### 标题：Dimensionality Reduction and Denoising of Spatial Transcriptomics Data Using Dual-channel Masked Graph Auto-encoder
### 摘要：
In this paper, we propose an efficient self-supervised learning method utilizing a **dual-channel masked graph autoencoder**  for the analysis and research of spatial transcriptomics data (namely **STMask**). The gene representation learning channel cleverly integrates the masking mechanism into the graph autoencoder, reducing feature redundancy and enhancing model robustness. Additionally, we employ the scaled cosine loss as the training objective to further stabilize the embedding representation. Simultaneously, the gene relationship learning channel disrupts the spatial graph structure to generate multiple perspectives and combines contrastive learning principles to maximize mutual information, thereby strengthening the model's discriminative capability. It is worth noting that the two channels share the same encoder, which helps to enhance the model's ability to learn gene expressions and facilitates the acquisition of discriminative feature embeddings. 
![STMask.jpg](STMask.jpg)

### 引用
<p>The corresponding BiBTeX citation are given below:</p>
<div class="highlight-none"><div class="highlight"><pre>
@article{min2019,
author       = {Wenwen Min, Juan Liu, Shihua Zhang},
title        = {Dimensionality Reduction and Denoising of Spatial Transcriptomics Data Using Dual-channel Masked Graph Auto-encoder},
month        = {June},
year         = {2024},
note         = {\url{https://ieeexplore.ieee.org/document/8782829}},
}</pre></div>
