# LightGBM
Some study about LightGBM


## 参考  https://github.com/microsoft/LightGBM/tree/master/examples/regression
1. simple_example 包括

- 创建数据集
- 训练集中划分验证集
- 保存和加载模型
- early_stopping_rounds 设置早停

2. sklearn_example 包括

- 不同的训练和验证方式
- 自己设置评价指标
- 得到对结果影响较大的特征
- 网格搜索和交叉验证调参

3. advanced_example 包括

- 设置每一列的权重，和重复使用数据
- 保存成三种格式的模型
- 加载模型并继续训练
- callbacks更改训练过程中的参数
- 自定义目标函数和验证函数
