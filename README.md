1、工业蒸汽量预测
处理步骤：
（1）将相关系数小于0.1的特征去除；
（2）6个训练集和测试集差别太大特征去除；
（3）将训练集和测试集分别进行归一化处理（sklearn.preprocessing.MinMaxTransformer;
（4）然后将数据进行偏态处理(sklearn.preprocessing.PowerTransformer);
（5）构建ridge regression模型，调参 alpha=250，提交结果；
（6）MSE=0.1426。


