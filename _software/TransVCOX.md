---
title: "MAVAE"
collection: software
permalink: /software/TransVCOX
date: 2024-06-04
---

<!-- 标题 -->
### TransVCOX: Bridging Transformer Encoder and Pre-trained VAE for Robust Cancer Multi-Omics Survival Analysis[[GitHub](https://github.com/wenwenmin/TransVCOX)]
### 摘要
Traditional survival analysis models, such as the COX proportional hazards model, face challenges in processing multimodal data, identifying nonlinear relationships, and recognizing complex data patterns. The rise of deep learning, particularly Transformers and variational autoencoders (VAEs), has showcased its potential in analyzing cancer multi-omics data comprehensively. However, many individual cancer datasets suffer from limited sample sizes, preventing some deep learning models from extracting in-depth data representations and resulting in subpar performance.
To address this issue, we advocate the adoption of pre-training and fine-tuning techniques, which effectively mitigate performance deficits due to sparse cancer data samples. We introduce TransVCOX, a deep survival analysis model integrating a Transformer encoder with VAE. This model leverages pre-training and fine-tuning approaches to predict patients' survival risk using cancer multi-omics data.
Rigorous tests on eight unique cancer datasets from TCGA revealed:
(1) TransVCOX outperforms other deep learning and conventional COX models.
(2) Pre-training significantly reduces model overfitting and enhances performance.
(3) VAE encoding, compared to positional encoding, offers a richer decision-making foundation.
(4) The performance boost doesn't linearly correlate with the addition of Transformer blocks.
These findings underline TransVCOX's promising capability for predicting cancer patients' survival risks using multi-omics data. 
<!-- 论文模型图 -->

<p align="center"> 
<img src="../images/TransVCOX.png">
</p>


### 论文状态
- BIBM2023<br>

### 论文引用
<p>The corresponding BiBTeX citation are given below:</p>
<div class="highlight-none"><div class="highlight"><pre>
@inproceedings{li2023transvcox,
  title={TransVCOX: Bridging Transformer Encoder and Pre-trained VAE for Robust Cancer Multi-Omics Survival Analysis},
  author={Li, Xiaoyu and Min, Wenwen and Chen, Jinyu and Wu, Jiaxin and Wang, Shunfang},
  booktitle={2023 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)},
  pages={1254--1259},
  year={2023},
  organization={IEEE}
}


</pre></div>

