# Hi 👋
我是中山大学研三在读学生~目前从事高光谱图像处理工作，以下是我的一些开源项目和学习笔记。未来将在企业担任NLP算法工程师一职。

# 开源项目🔭

## [IMOPSO](https://github.com/liurongwhm/IMOPSO-EBE)
针对多目标粒子群优化算法全局搜索能力不足，难以获取优质端元组合的问题，构建基于光谱子空间的多目标优化模型，以获取更为完整的端元集合；设计竞争与合作机制和聚类子空间搜索机制以改进多目标粒子群优化算法，提升了算法的全局搜索能力与搜索效率，并赋予粒子整合优质信息的能力。
> R. Liu, P. Wang, B. Du and B. Qu, "Endmember Bundle Extraction Based on Improved Multiobjective Particle Swarm Optimization," IEEE Geoscience and Remote Sensing Letters, vol. 20, pp. 1-5, 2023, Art no. 5506405, doi: 10.1109/LGRS.2023.3287919.

## [MAT-Net]([https://github.com/liurongwhm/IMOPSO-EBE](https://github.com/WangPengrui/MAT-Net))
基于ViT设计了一种CNN-Transformer混合模型[1]，利用Transformer聚合CNN提取的多尺度特征信息，用于提取卫星图像中不同地物类型（如树木，屋顶等）的特征信息，同时估算图像中每个像素内部包含的地物类型及其所占面积的比例。解混任务可通俗理解为一种图像软分类任务，即像素级估算所属不同地物类型的概率。
- 提出双流多分支CNN编码器以提取高光谱图像的光谱特征和不同尺度的空间特征。
-	提出多头自尺度聚合注意力机制构建Transformer编码器，融合多尺度特征，相较SOTA解混精度提升16.1%。
> Wang P, Liu R, Zhang L. MAT-Net: Multiscale Aggregation Transformer Network for Hyperspectral Unmixing[J]. IEEE Transactions on Geoscience and Remote Sensing, 2024.

## 一些分享

- [E-FDPC-julia](https://github.com/WangPengrui/E-FDPC-julia)：增强密度峰值快速聚类算法（Enhanced-fast density-peak-based clustering, [E-FDPC](https://github.com/senjia1980/EFDPC)）的julia实现。

## 更多内容

- MOMSC：一种基于遗传算法的端元数提取问题，着重于解决优化算法用于组合优化问题的棘手个体退化问题，大修审稿中...

# 学习心得🌱
写一些小笔记，促进自身成长。

## Leetcode
- 数据结构和算法的学习心得会放在[这里](https://github.com/WangPengrui/leetcode-learing)。（TODO...）
- [卡码网](https://kamacoder.com/)个人[答案](https://github.com/WangPengrui/leetcode-learing/tree/main/kama)分享。

## Java
- TODO...

## flutter
- 一些基础语法和基础入门项目，[传送门](https://github.com/WangPengrui/flutter-learing)。



<!--
**WangPengrui/WangPengrui** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
 
