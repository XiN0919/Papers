# Transfer Learning Paper Record

## [Domain Adaptation Paper](https://github.com/XiN0919/Transfer-Learning-Paper/tree/main/Domain%20Adaptation)

| Number | Paper Name|  Published | Motivation | Inspired |
| :-: | :---: | :---: | :-- | :--- |
| 14 | [Semi-Supervised Domain Adaptation by Similarity based Pseudo-label Injection](https://arxiv.org/abs/2209.01881) | ECCV<br>2022 | （SSDA）分为四个部分：1）Domain Alignment：通过有标签的目标域与源域进行特征对比学习；2）Soft Pseudo-labeling：无参化，通过相似度生成；3）Intra-domain Similarity：无标签目标域相似的特征表示样本距离拉近；4）Pseudo-label Injection:标志注入，更新有标签目标域数据 | 个人感觉非常好的一篇论文，可以更深入挖掘 |
| 11 | [Align and Adapt: A Two-stage Adaptation Framework for Unsupervised Domain Adaptation](https://dl.acm.org/doi/abs/10.1145/3503161.3547973) | MM<br>2022 | 二阶段对比学习方法 | 与想法有冲突，不过从整体观、思路方面不同 |
| 10 | [FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence](https://proceedings.neurips.cc/paper/2020/hash/06964dce9addb1c5cb5d6e3d9838f733-Abstract.html) | NIPS<br>2020 | 利用数据强弱增强的预测一致性来约束伪标签 | 一种伪标签的好方法 |
| 9 | [Minimum Class Confusion for Versatile Domain Adaptation](https://link.springer.com/chapter/10.1007/978-3-030-58589-1_28) | ECCV<br>2020 |  |  |
| 8 | [Bridging Theory and Algorithm for Domain Adaptation](https://arxiv.org/pdf/1904.05801.pdf) | ICML<br>2019 |  |  |
| 7 | [Larger Norm More Transferable: An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation](https://ieeexplore.ieee.org/document/9009009) | ICCV<br>2019<br>最佳提名 | 通过VisDA2017源模型上源域和目标域样本的特征可视化推导了两个假设：错位特征范数假设与较小特征范数假设。在每次迭代中，将特征范数自适应应用于任务特定的特征。而对应两个假设，作者提出两种新的域适应方法：对于AFN的硬变换与逐步变换。硬变换在实验中证明之前的假设错误，而在逐步变换SAFN中，当前的特征范数要接近于上一次迭代的特征二范数+r，以渐进的方式学习具有更大范数的特定任务特征 | 偏理论方向，代码实现容易 |
| 6 | [Maximum Classifier Discrepancy for Unsupervised Domain Adaptation](https://openaccess.thecvf.com/content_cvpr_2018/html/Saito_Maximum_Classifier_Discrepancy_CVPR_2018_paper.html) | CVPR<br>2018 | MCD：固定Genarator，最大化距离，调整分类器决策边界；固定Classifier,最小化距离进行适配 | 实验部分多了Semantic Segmentation |
| 5 | [Conditional Adversarial Domain Adaptation](https://proceedings.neurips.cc/paper/2018/hash/ab88b15733f543179858600245108dd8-Abstract.html) | NIPS<br>2018 | CDAN：条件域对抗网络设计有两种新的调节策略:多线性条件，捕获特征表示和分类器预测之间的互协方差以提高可区分性；熵条件，控制分类器预测的不确定性以保证可传递性 |  |
| 4 | [Adversarial Discriminative Domain Adaptation](https://ieeexplore.ieee.org/document/8099799) | CVPR<br>2017 | ADDA：思想巧妙，有点构造辅助任务的意思 | 文章部分表述可借鉴；混淆矩阵 |
| 3 | [Deep Transfer Learning with Joint Adaptation Networks](http://proceedings.mlr.press/v70/long17a.html) | ICML<br>2017 | JMMD距离 | 公式写作 |
| 2 | [Domain-Adversarial Training of Neural Networks](https://www.jmlr.org/papers/volume17/15-239/15-239.pdf) | JMLR<br>2016 | 域判别器+梯度反转层 | 期刊论文-期刊写作可借鉴 |
| 1 | [Learning Transferable Features with Deep Adaptation Networks](https://arxiv.org/pdf/1502.02791.pdf) | ICML<br>2015 | DAN：1）特征提取器前几层frozen； 2）特征提取器后几层微调；3）6-8层计算MK-MMD拉近源域目标域距离--针对特定任务 | 特征可视化（只画目标域特征）；A-Distance距离 |


## [Domain Generalization Paper](https://github.com/XiN0919/Transfer-Learning-Paper/tree/main/Domain%20Generalization)

| Number | Paper Name|  Published | Motivation | Inspired |
| :-: | :---: | :---: | :-- | :--- |
|   | |  |  |  |  |
| 2 | [Semantic-Aware Domain Generalized Segmentation](https://ieeexplore.ieee.org/document/9879987/) | CVPR<br>2022 | 主要是了解该论文的白化模块 | 论文写作非常好 | 
| 1 | [Domain Generalization With MixStyle](https://openreview.net/forum?id=6xHJ37MVxxp) | ICLR<br>2021 | 提出利用Instance Normalization + 样本mu、sig进行风格混合（类似于一种加噪声） | 模块即插即用，方便(尝试了层次化、白化等，效果不好) |

## [Test Time Adaptation Paper](https://github.com/XiN0919/Transfer-Learning-Paper/tree/main/Test%20Time%20Adaptation)

| Number | Paper Name|  Published | Motivation | Inspired |
| :-: | :---: | :---: | :-- | :--- |
| 6|[Contrastive Test-Time Adaptation](https://ieeexplore.ieee.org/document/9880363/) |CVPR<br>2022 | 对比学习引入TTA的研究中 | 对比学习对无监督、伪标签这块研究有帮助 |
| 5|[Efficient Test-Time Model Adaptation without Forgetting](https://proceedings.mlr.press/v162/niu22a.html) |ICML<br>2022| 防止网络参数变化过大以及主动样本更新网络参数 | 主动样本挑选 |
| 4|[TENT:Fully Test-Time Adaptation By Entropy Minimization](https://openreview.net/forum?id=uXl3bZLkr3c) |ICLR<br>2021| 熵最小化的方式在Test-Time时更新模型 |   熵最小化的应用 |
| 3|[Test-Time Classifier Adjustment Module for Model-Agnostic Domain Generalization](https://proceedings.neurips.cc/paper/2021/hash/1415fe9fea0fa1e45dddcff5682239a0-Abstract.html) | NIPS<br>2021 |  |  |
| 2|[TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive](https://proceedings.neurips.cc/paper/2021/hash/b618c3210e934362ac261db280128c22-Abstract.html) | NIPS<br>2021 | 相较于TTT，多保留了源域的mu、sig，在TTA阶段计算源域和目标域mu、sig距离 | 源域的统计量信息 |
| 1|[Test-Time Training with Self-Supervision for Generalization under Distribution Shifts](http://proceedings.mlr.press/v119/sun20b.html) | ICML<br>2020 | 提出了TTA问题，仅在目标域测试时调整模型（辅助任务） | 新的研究方向（已研究比较完善了） |