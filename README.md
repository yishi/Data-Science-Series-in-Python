# Data-Science-Series-in-Python

[01 数据科学的基础——基本统计概念的介绍](http://nbviewer.jupyter.org/github/yishi/Data-Science-Series-in-Python/blob/master/the_introduction_of_data_science_01.ipynb)

这部分介绍了一些基本的统计概念，主要是考虑到部分同学，一般对方差的实际意义很模糊，对中位数与平均数的适用场景不清晰，以及对箱线图和小提琴图的不熟悉。

- 查看连续变量，使用直方图
- 汇总连续变量，描述变量的集中位置，使用均值
- 存在异常值的数据，新旧均值的对比，引入中位数
- 汇总连续变量，描述变量的分散程度，引入方差、标准差的概念
- 存在异常值的数据，引入四分位距，介绍箱线图
- 大量增加异常值，汇总统计量不适用的场景，引入小提琴图。


[02 数据科学的模型——分类模型基础知识](http://nbviewer.jupyter.org/github/yishi/Data-Science-Series-in-Python/blob/master/the_introduction_of_data_science_02.ipynb)

这部分以鸢尾花数据集为例

- 先是简单的数据探索
- 然后手动构建一个简单的分类器
- 随后引入决策树模型
- 又根据模型效果的思考，引入数据的拆分，如训练集和验证集的拆分，k重交叉检验的拆分
- 随后介绍针对分类模型的评价方法，如混淆矩阵，precision，recall等指标，ROC曲线，PR曲线。


[03 数据科学的模型——分类模型简介](http://nbviewer.jupyter.org/github/yishi/Data-Science-Series-in-Python/blob/master/the_introduction_of_data_science_03.ipynb)                                                                                    

这部分介绍了一些分类模型

- 先介绍了逻辑回归的基本原理，用鸢尾花数据集画了分类边界；
- 随后依次介绍了k最近邻算法、朴素贝叶斯分类器、支持向量机、集成算法（如装袋算法、随机森林、提升算法等）；
- 最后以手写体数字数据集为例，使用各分类模型识别手写体数字，k最近邻算法效果最好。
