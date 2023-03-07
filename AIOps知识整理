# HDD&SSD硬盘故障预测
## 论文
* NTAM: Neighborhood-Temporal Attention Model for Disk Failure Prediction in Cloud Platforms
* An In-Depth Study of Correlated Failures in Production SSD-Based Data Centers
* Toward Adaptive Disk Failure Prediction via Stream Mining
* Robust Data Preprocessing for Machine-Learning-Based Disk Failure Prediction in Cloud Production Environments
* Making Disk Failure Predictions SMARTer!
* System-level hardware failure prediction using deep learning
## PCA
* [PCA原理](https://zhuanlan.zhihu.com/p/37777074)
* [PCA异常检测](https://zhuanlan.zhihu.com/p/29091645)
* [逆矩阵计算](https://www.shuxuele.com/algebra/matrix-inverse.html)，[特征值和特征向量计算](https://blog.csdn.net/Junerror/article/details/80222540)
* [协方差表示相关性](https://www.zhihu.com/question/20852004)，协方差为正->同向变化，协方差为负->反向变化
* [PCA数学原理](http://blog.codinglabs.org/articles/pca-tutorial.html)
## [相关系数](https://blog.csdn.net/zhaozhn5/article/details/78392220)
* [Pearson相关系数和Spearman相关系数的区别](https://blog.csdn.net/Android_xue/article/details/100136612)，pearson为线性关系（与变化量有关），spearman为单调关系（仅与趋势有关），spearman对数据错误和极端值不敏感
## [随机森林](https://cloud.tencent.com/developer/article/1749077)
* 分类树寻找分割点时最小化基尼系数，回归树最小化平方误差
* 调参一般调整树的个数、最小叶子节点数和最大深度，以及是否balance
# HDD加速扫描
# 慢盘检测
# 高危命令检测
## DBSCAN
* [DBSCAN原理](https://www.cnblogs.com/pinard/p/6208966.html)
* [sklearn中DBSCAN参数和属性](https://scikit-learn.org.cn/view/379.html)，https://www.cnblogs.com/pinard/p/6217852.html, DBSCAN中噪声样本被划分为-1类 
* 无法确定类别数k值时，使用DBSCAN而不是kmeans
### [余弦相似度](https://blog.csdn.net/u010847579/article/details/88893107)
* 余弦相似度为向量间夹角余弦值，余弦距离 = 1-余弦相似度
* 余弦距离体现方向上的相对差异，欧式距离体现数值上的绝对差异。在文本、图像、视频等领域，或使用词频或词向量作为特征时，因为特征维度很高且每个维度都表示一个特征，一般使用余弦相似度来度量，https://www.zhihu.com/question/19640394,https://blog.csdn.net/leitouguan8655/article/details/80589654
## FastText
* [fasttext原理及与word2vec的差异](https://zhuanlan.zhihu.com/p/49972507)
## K-Means
* [K-Means原理](https://www.cnblogs.com/pinard/p/6164214.html)
* [sklearn中kmeans参数和属性](https://blog.csdn.net/weixin_41724761/article/details/89786414)
* [手肘法和轮廓系数选择最优聚类数k值](https://www.jianshu.com/p/335b376174d4)，https://jjzhou012.github.io/blog/2021/02/07/Tutorials-determine-K-means-best-K.html
# 模型失效检测
## [动态时间规整算法DTW](https://zhuanlan.zhihu.com/p/72542821)
* 可用python中[fastdtw](https://pypi.org/project/fastdtw/)库实现
* 用动态规划方法计算两个时间序列长度不等的情况下从（1,1）到（m,n）的最短距离，m=n时可直接使用对应点间的欧式距离计算
## 回声神经网络
## DTW算法
# 告警
## 告警分析
## 告警压缩
* [常用相似度和距离计算方法](https://codeantenna.com/a/HHiTXO1OdV)
* [字符串相似性度量方法](https://www.cnblogs.com/djdjdj123/p/11799508.html)：杰卡德距离，编辑距离，余弦相似度
* [告警压缩方案](https://cloud.tencent.com/developer/article/1662672)
* 计算告警名的jaccard相似度>0.7
* 学习[文本相似度](https://blog.csdn.net/qq_28031525/article/details/79596376)知识？？？？
* [jieba分词 + jaccard相似度计算](http://www.codebaoku.com/it-python/it-python-237045.html)
* [Jaccard与cosine文本相似度的异同](https://zhuanlan.zhihu.com/p/60723017)，[词袋模型与TF-IDF](https://blog.csdn.net/u012328159/article/details/84719494)，可通过词袋模型或TF-IDF或word2vec将告警名转变为向量再计算余弦相似度
# 日志
## 日志模板提取
## 日志异常检测
* [tf-idf](https://blog.csdn.net/asialee_bird/article/details/81486700)
# 异常检测
## 标准boxplot异常检测
## KPI异常检测
## IO异常检测
## 网络异常检测
# 内存故障预测
# cpu故障预测
# 根因诊断
## 多维指标下钻分析
* [Adtributor算法(MDRCA)](https://cloud.tencent.com/developer/article/1644348)，[代码实现](https://developer.aliyun.com/article/849247)
## 相关轮文
* 基于日志、基于trace和基于监控指标，https://cloud.tencent.com/developer/article/1877473
## 基于知识图谱的根因诊断
容量预测，告警分析，日志模板提取，告警压缩，告警聚合，根因诊断RCA等

Drools，neo4j，cypher

仿真建模软件有哪些，sbip
告警聚合、告警压缩，告警关联
图谱构建、图谱推理，推导模型，规则引擎
多维下钻诊断，日志压缩
日志模板提取，日志异常诊断
看IFPP上每个模块的代码，学习一下整个智能运维领域
MDRCA,CCRCA
告警关联分析
