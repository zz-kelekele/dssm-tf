# dssm-tf

> 尝试通过tf里面的estimator接口实现了一个简单的dssm的算法

### 说明

1. 输入数据为通过“\t”分割的数据
2. 输入数据的schema通过conf文件夹里面的schema文件控制
3. 模型训练中使用到的feature通过conf文件夹里面的feature文件控制
4. 其他参数通过train.yaml和model.yaml控制
5. 一些逻辑部分参考了https://github.com/Lapis-Hong/wide_deep