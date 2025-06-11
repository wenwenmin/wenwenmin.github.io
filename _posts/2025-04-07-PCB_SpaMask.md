---
title: 'SpaMask 正式发表在 PLoS Computational Biology'
date: 2025-04-08
permalink: /posts/2025-04-07-PCB_SpaMask
tags:
  - cool posts
  - category1
  - category2
---

#### 🎉 我们课题组近期的一项工作 **SpaMask** 正式发表在 _PLoS Computational Biology_！

🔬 **SpaMask：一种面向空间转录组数据分析的自监督图神经网络方法**

💡 在空间转录组数据分析中，空间域识别是理解组织结构和细胞异质性的关键。我们提出的 SpaMask 方法创新性地结合了 **掩码机制** 、 **图神经网络**与**对比学习机制** ，设计了 **掩码图自编码（MGAE）** 和 **掩码图对比学习（MGCL）** 两个模块，能够在不依赖标签的情况下，有效提升聚类精度、鲁棒性和平台间的适应性。 

MGAE通过节点掩码机制，充分利用细胞空间邻域信息，实现更精准的空间域聚类，极大地提高了聚类准确率。MGCL应用边掩码策略构建对比损失框架，使得相邻节点（在空间上邻近且特征相似）获得更紧密的嵌入表示，从而提升了模型的鲁棒性和批次效应校正能力。

![SpaMask](https://github.com/wenwenmin/SpaMask/blob/main/SpaMask.jpg?raw=true)

🔥🔥🔥 我们在来自 **5个不同平台的8个空间转录组数据集** 上进行了全面的评估，结果显示 SpaMask 在**聚类性能**和**批次效应消除**等方面均优于现有方法。

🚀 为便于使用，我们已将 SpaMask 的全部代码和数据集上传至：

-   💻 [GitHub 开源代码](https://github.com/wenwenmin/SpaMask)

-   📁 [Zenodo 数据集下载](https://zenodo.org/records/14062665)


🌐 此外，我们课题组在空间转录组学多个核心问题上已开发出一系列工具，包括：

-   **SpaDiT**：用于扩散模型进行空间转录组学数据的基因预测
    
-   **SpaViT**：通过基于ViT的自监督学习思想以生成高密度空间基因表达
    
-   **SpaBatch**：面向跨切片/跨平台批次效应消除
    
-   **scstGCN**：基于通用基础模型和图神经网络的超分辨率基因表达推测方法
    
-   **mclSTExp**：使用对比学习方法从组织学图像中预测基因表达
    

这些工具的**全部代码**也都已开放，欢迎访问我们的  **[GitHub](https://github.com/wenwenmin/)** 页面获取并使用！

📢 欢迎感兴趣的同仁试用、批评、指正，也欢迎交流合作！
