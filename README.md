# Transfer Learning Paper Record

## [Domain Adaptation Paper](https://github.com/XiN0919/Transfer-Learning-Paper/tree/main/Domain%20Adaptation)

| Number | Paper Name|  Published | Motivation | Inspired |
| :-: | :---: | :---: | :-- | :--- |
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
| 1 | [Domain Generalization With MixStyle](https://openreview.net/forum?id=6xHJ37MVxxp) | ICLR<br>2021 | 提出利用Instance Normalization + 样本mu、sig进行风格混合（类似于一种加噪声） | 模块即插即用，方便 |

## [Test Time Adaptation Paper](https://github.com/XiN0919/Transfer-Learning-Paper/tree/main/Test%20Time%20Adaptation)

| Number | Paper Name|  Published | Motivation | Inspired |
| :-: | :---: | :---: | :-- | :--- |
| 6|[Contrastive Test-Time Adaptation](https://ieeexplore.ieee.org/document/9880363/) |CVPR<br>2022 |  |  |
| 5|[Efficient Test-Time Model Adaptation without Forgetting](https://proceedings.mlr.press/v162/niu22a.html) |ICML<br>2022|  |  |
| 4|[TENT:Fully Test-Time Adaptation By Entropy Minimization](https://openreview.net/forum?id=uXl3bZLkr3c) |ICLR<br>2021|  |  |
| 3|[Test-Time Classifier Adjustment Module for Model-Agnostic Domain Generalization](https://proceedings.neurips.cc/paper/2021/hash/1415fe9fea0fa1e45dddcff5682239a0-Abstract.html) | NIPS<br>2021 |  |  |
| 2|[TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive](https://proceedings.neurips.cc/paper/2021/hash/b618c3210e934362ac261db280128c22-Abstract.html) | NIPS<br>2021 |  |  |
| 1|[Test-Time Training with Self-Supervision for Generalization under Distribution Shifts](http://proceedings.mlr.press/v119/sun20b.html) | ICML<br>2020 |  |  |
