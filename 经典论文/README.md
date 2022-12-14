# Semi-Supervised Paper Record
| Number | Paper Name|  Published | Motivation |
| :-: | :---: | :---: | :-- |
| 7 | []() | <br> |  |
| 6 | [Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/abs/2111.06377) | CVPR<br>2022 | MAE：BERT的CV版本，通过mask patch重构像素的方式进行预训练，下游任务可能只需要encoder即可 |
| 5 | [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929) | ICLR<br>2021 | VIT：Vision Transformer图片输入打成patch，每个patch相当于一个单词，Transformer架构不变，打通了NLP和CV鸿沟 |
| 4 | [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805) | NAACL<br>2019 | BERT：双向Transformer，自监督填词训练，开启了预训练的时代 |
| 3 | [Attention Is All You Need](https://proceedings.neurips.cc/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html) | NIPS<br>2017 | Transformer：Self-Attention替换之前的CNN、RNN，优缺点及具体见纸质论文记录 |
| 2 | [Deep residual learning for image recognition](https://openaccess.thecvf.com/content_cvpr_2016/html/He_Deep_Residual_Learning_CVPR_2016_paper.html) | CVPR<br>2016 | ResNet：解决网络层数变深，性能下降的问题，学习残差；理论解释少，可以从梯度角度解释为什么训练速度快 |
| 1 | [ImageNet classification with deep convolutional neural networks](https://dl.acm.org/doi/abs/10.1145/3065386) | NIPS<br>2012 | AlexNet五层卷积+三层全连接，文章双卡训练，模型切开细节见原文 |
