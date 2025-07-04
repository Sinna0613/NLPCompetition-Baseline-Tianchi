# NLPCompetition-Baseline-Tianchi

- 项目网址：https://tianchi.aliyun.com/competition/entrance/532331?spm=a2c22.29524732.0.0.1ed43b74TmD1GT
- 该项目为阿里天池【NLP系列学习赛】寻址大师：地址相关性判断的代码
- 模型仅对训练数据进行学习，未对测试集进行验证
- 数据集为官方下载

-------------

- 项目采取的主要创新点有：
- 1.Focal loss损失函数：处理样本中三类数据的严重不平衡情况
- 2.FGM对抗训练
- 3.N-gram掩码
- 2&3均显著提升了模型的训练效果
