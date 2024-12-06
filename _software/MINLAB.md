---
title: "STMask1"
collection: software
permalink: /software/STMask
date: 2024-06-04
---

<!-- 标题 -->
### Dimensionality Reduction and Denoising of Spatial Transcriptomics Data Using Dual-channel Masked Graph Auto-encoder [[GitHub](https://github.com/donghaifang/STMask/tree/main)]
### 摘要
We propose an efficient self-supervised learning method utilizing a **dual-channel masked graph autoencoder**  for the analysis and research of spatial transcriptomics data (namely **STMask**). The gene representation learning channel cleverly integrates the masking mechanism into the graph autoencoder, reducing feature redundancy and enhancing model robustness. Additionally, we employ the scaled cosine loss as the training objective to further stabilize the embedding representation. Simultaneously, the gene relationship learning channel disrupts the spatial graph structure to generate multiple perspectives and combines contrastive learning principles to maximize mutual information, thereby strengthening the model's discriminative capability. It is worth noting that the two channels share the same encoder, which helps to enhance the model's ability to learn gene expressions and facilitates the acquisition of discriminative feature embeddings. 
<!-- 论文模型图 -->
<p align="center"> 
<img src="../images/STMask.jpg">
</p>

### 论文状态
- 投稿PLoS CB 2024.5<br>
- [BioRxiv](https://www.biorxiv.org/content/10.1101/2024.05.30.596562v1)

### 论文引用
<p>The corresponding BiBTeX citation are given below:</p>
<div class="highlight-none"><div class="highlight"><pre>
@article{STMask2024,
author       = {Wenwen Min, Donghai Fang Jinyu Chen and Shihua Zhang},
title        = {Dimensionality Reduction and Denoising of Spatial Transcriptomics Data Using Dual-channel Masked Graph Auto-encoder},
year         = {2024}
}
</pre></div>

---
title: "STMask2"
collection: software
permalink: /software/STMask
date: 2024-06-04
---

<!-- 标题 -->
### Dimensionality Reduction and Denoising of Spatial Transcriptomics Data Using Dual-channel Masked Graph Auto-encoder [[GitHub](https://github.com/donghaifang/STMask/tree/main)]
### 摘要
We propose an efficient self-supervised learning method utilizing a **dual-channel masked graph autoencoder**  for the analysis and research of spatial transcriptomics data (namely **STMask**). The gene representation learning channel cleverly integrates the masking mechanism into the graph autoencoder, reducing feature redundancy and enhancing model robustness. Additionally, we employ the scaled cosine loss as the training objective to further stabilize the embedding representation. Simultaneously, the gene relationship learning channel disrupts the spatial graph structure to generate multiple perspectives and combines contrastive learning principles to maximize mutual information, thereby strengthening the model's discriminative capability. It is worth noting that the two channels share the same encoder, which helps to enhance the model's ability to learn gene expressions and facilitates the acquisition of discriminative feature embeddings. 
<!-- 论文模型图 -->
<p align="center"> 
<img src="../images/STMask.jpg">
</p>

### 论文状态
- 投稿PLoS CB 2024.5<br>
- [BioRxiv](https://www.biorxiv.org/content/10.1101/2024.05.30.596562v1)

### 论文引用
<p>The corresponding BiBTeX citation are given below:</p>
<div class="highlight-none"><div class="highlight"><pre>
@article{STMask2024,
author       = {Wenwen Min, Donghai Fang Jinyu Chen and Shihua Zhang},
title        = {Dimensionality Reduction and Denoising of Spatial Transcriptomics Data Using Dual-channel Masked Graph Auto-encoder},
year         = {2024}
}
</pre></div>


---
title: "stMCDI"
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
- [arXiv](https://arxiv.org/abs/2403.10863)

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
