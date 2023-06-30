# lableme-post-process
使用lableme标注的多边形区域图像，处理得到两种图像：每一个object的mask图像和mask的最小外接矩形框。

本项目的出发点是：为了使用sam模型进行模型再训练，看到了一篇帖子https://zhuanlan.zhihu.com/p/627098441。
但是，他的数据集是邮票数据集https://www.kaggle.com/datasets/rtatman/stamp-verification-staver-dataset，跑通了这个项目。
但是，想要训练自己的数据集，就要构造和这个数据集一样的数据。那么，怎么得到呢？于是，就有了这篇帖子。

