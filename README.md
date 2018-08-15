本项目是一个情感分析的项目，目标是输入一段文本然后判断这段文本的情绪。文本是英文。
原始数据集中的目标分类一共有6个，分别是 toxic, severe_toxic, obscene, threat, insult, identity_hate. 
使用 AUC 来评估模型的性能。

step 1：
处理数据，对应的是 preparation 文件。

step 2：
模型相关代码，对应的是 toxic_model 文件。思路是对每个分类都训练一个模型，每个模型构建的代码都是一样的，只是参数调整方面略微不同，所以这里只放出了 toxic 分类模型，其他模型可以依葫芦画瓢。
