  近年来，随着微信、微博、市长信箱、阳光热线等网络问政平台逐步成为政府了解民意、汇聚民智、凝聚民气的重要渠道，各类社情民意相关的文本数据量不断攀升，给以往主要依靠人工来进行留言划分和热点整理的相关部门的工作带来了极大挑战。同时，随着大数据技术的发展，建立基于自然语言处理技术的智慧政务系统已经是社会治理创新发展的新趋势，对提升政府的管理水平和施政效率具有极大的推动作用。

  本文针对“智慧政务”中的居民投诉建议文本评论数据，基于向量空间模型算法提取了文本关键词并我们采用了多种机器学习分类模型进行测试，从最终得到线性支持向量回归算法相对较优的结果，F1-Score评价指标达0.86。

  在挖掘热点问题的前期处理上，使用了余弦相似度计算整理出文本相似的同类主题并加以筛选，通过在SPSS中建立基于因子分析法的热度评价指标模型，给出得分前五的主题样本作为Top5热点问题，分析比较了相关类问题的热度体现在各个指标上的具体表现。

  为建立留言的答复意见的评价体系，我们定义了相关性、完整性、可解释性和及时性四个指标。答复意见和留言详情相关性的计算是基于LDA主题模型的中文编辑距离得到的，另外答复意见的可解释性使用了哈工大中文篇章关系的关联词表以及自定义的可解释性词典来判别。通过将这四项指标的得分相加得到某条答复意见的综合评分，分数越高，该答复的质量就越高，从而为决策者提供一个较为清晰完善的参考意见。
