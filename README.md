# 原文https://blog.csdn.net/qq_33431368/article/details/125925577
## 原文把原始数据集加上了表头，整理了文件顺序，我把整理好的文件上传上来。

SMD数据集 出自论文：Robust Anomaly Detection for Multivariate Time Series through Stochastic RNN
## 数据集详情
SMD数据集(Server Machine Dataset)
相关链接：https://github.com/NetManAIOps/OmniAnomaly
出自论文：Robust Anomaly Detection for Multivariate Time Series through Stochastic RNN
Netman收集
信息
5周数据（时间粒度是1min，数据中时间index省略）
28个不同的机器对应28个实体，每个实体有38维度的数据（每个维度都是机器的metric）
数据量=57246028=1411200
训练集和测试集=1:1，训练集无label，测试集有label
原始文件说明
train: The former half part of the dataset.
machine-x-y.txt 其中x代表组，y是组里的index，每一个machine-x-y代表一个具体的机器即实体。
test: The latter half part of the dataset.
test_label: The label of the test set. It denotes whether a point is an anomaly.
