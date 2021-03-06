# 创新部分说明
## 一. 通过均方差评估下不同参数下回归模型的能力
在此例程中，我采用逻辑回归算法对鸢尾花数据进行分类。为了探究不同参数下回归模型的能力，我对 LogisticRegression()函数中的参数 C 进行了多次修改，并计算不同参数下的 MSE， 最后通过折线图进行了数据可视化。可以看出，随着 C 的增大，MSE 呈下降趋势，预测效果更准确。C 增大到一定程度后，MSE 基本不变。
## 二. 对于matplotlib的使用
我写了一篇文档，简单说明了matplotlib的基本使用方法。（附件1_matplotlib的使用.pdf）
## 三. 不同聚类数量对于结果的区别
为了验证聚类数量对结果的影响，我多次改变 KMeans() 函数里 n_clusters 的值，并分别输出结果。通过输出的结果发现，聚类数量越多，分类越细致，所分的类数越多。而且，如果只显示flower1、flower2和flower3的预测结果时，聚类数量越多，三种花的分界越明显。
## 四. 用不同的特征进行特征聚类会有什么结果
经查阅资料，我了解到鸢尾花数据集中包含了鸢尾花的四个特征，分别为花萼长度，花萼宽度，花瓣长度，花瓣宽度。对于本道题，我修改了选择的特征，将花萼长度和花萼宽度修改为花瓣长度和花瓣宽度。
## 五. 尝试更多的数据集
我模仿课上学过的算法，对波士顿房价这个数据集进行了线性回归预测。
## 六. 进行2007年前中国男足在亚洲水平的聚类实验
我把ppt里的男足的2007年前的成绩数据整理成了表格，然后对这个数据集进行聚类分类，最终输出了分类结果。
