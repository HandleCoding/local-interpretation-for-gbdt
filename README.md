
### 背景

集成树方法如随机森林（Random Forest，RF）、梯度提升树（Gradient Boosing Decision Tree, GBDT）及其变种XGBoost等由于其良好的拟合能力和模型解释性，在金融、医学统计等诸多领域有广泛的应用。

一般的RF、GBDT或XGBoost模型学习完毕后，模型会基于样本集得出各特征的重要性分数feature_importances，但是这种分数是基于样本整体得出的，模型学习完毕后各特征分数便已固定。而在实际应用中我们还关心模型对于特定个体在各个特征上的重要性评分分布，即局部解释性（local interpretation），以便于针对个体提出更精准的方案和建议。参考文献[1]中便提出了一种可以实现该目的的算法。



### 参考文献

1. W.J. Fang, J. Zhou, etc.: Unpack Local Model Interpretation for GBDT, 2018

   

### Jekyll主题

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Ulti-Dreisteine/local-interpretation-for-gbdt/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.



### 联系方式

- 我的邮箱：dreisteine262@163.com


