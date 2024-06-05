---
title: "STMask"
collection: software
permalink: /software/stMCDI
date: 2024-06-04
---

<!-- 标题 -->
### Masked Conditional Diffusion Model with GNN for Spatial Transcriptomics Data Imputation [[GitHub](https://github.com/lllxxyyy-lxy/stMCDI)]
### 摘要
Spatially resolved transcriptomics represents a significant advancement in single-cell analysis by offering both gene expression data and their corresponding physical locations. 
However, this high degree of spatial resolution entails a drawback, as the resulting spatial transcriptomic data at the cellular level is notably plagued by a high incidence of missing values.
Furthermore, most existing imputation methods either overlook the spatial information between spots or compromise the overall gene expression data distribution.
To address these challenges, our primary focus is on effectively utilizing the spatial location information within spatial transcriptomic data to impute missing values, while preserving the overall data distribution.
We introduce \textbf{stMCDI}, a masked conditional diffusion model for spatial transcriptomics data imputation, which employs a denoising network trained using randomly masked data portions as guidance, with the unmasked data serving as conditions. 
Additionally, it utilizes a GNN encoder to integrate the spatial position information, thereby enhancing model performance.
Compared with baseline methods, our model achieves state-of-the-art performance in all evaluation metrics on six real-world datasets.
The results obtained from spatial transcriptomics datasets elucidate the performance of our methods relative to existing approaches.
Our code can be accessed at \url{https://anonymous.4open.science/r/stMCDI-2824}.
<!-- 论文模型图 -->
<p align="center"> 
<img src="../images/stMCDI.png">
</p>


### 论文状态
- 投稿TNNLS 2024.4<br>
- [atXiv](https://arxiv.org/abs/2403.10863)

### 论文引用
<p>The corresponding BiBTeX citation are given below:</p>
<div class="highlight-none"><div class="highlight"><pre>
@article{li2024stmcdi,
  title={stMCDI: Masked Conditional Diffusion Model with Graph Neural Network for Spatial Transcriptomics Data Imputation},
  author={Li, Xiaoyu and Min, Wenwen and Wang, Shunfang and Wang, Changmiao and Xu, Taosheng},
  journal={arXiv preprint arXiv:2403.10863},
  year={2024}
}

</pre></div>

