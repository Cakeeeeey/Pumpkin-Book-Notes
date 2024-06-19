# 第一章 绪论
## 1.1 基本概念
- 机器学习：通过计算，利用数据（经验）改善系统自身性能
### 1.1.1 数据
- 数据集：样本sample/示例instance的集合
D={x1,x2,...xm}
- 样本sample/示例instance:包含研究对象在某方面的表现，即属性attribute(或特征feature)/属性值attribute value，是样本空间中的一个向量
Xi=(Xi1;Xi2;...Xid)
- 属性空间attribute space/样本空间sample space：把属性作为坐标轴构造的n维空间
- 特征向量feature vector：一个样本在样本空间中的坐标表示

### 1.1.2 训练目的
- 分类(classification)任务:预测离散值
- 回归(regression)任务:预测连续值
- 聚类(clustering)任务：把数据集分成若干组
### 1.1.3 训练方式
- 监督学习(supervised learning)：训练数据有标记信息，代表：分类、回归
- 无监督学习(unsupervised learning)：训练数据无标记信息，代表：聚类
### 1.1.4 模型能力
- 泛化(generalization)能力：模型适用于新样本（训练数据之外的数据）的能力
## 1.2 假设空间

