# DeepLearning_Bitmoji-Faces-Gender-Recognition_DenseNet-BC-model

### 深度学习作业——Kaggle比赛——Bitmoji Faces Gender Recognition——运用DenseNet-BC模型
- 在Kaggle的notebook中运行，直接添加Kaggle比赛中的数据集，代码中路径设置为了Kaggle上的路径。
- 运用GPU进行训练。
- 在读取权值的这一步：每次运行产生的文件都不一样，此处需要改变
> weight_filepath = "/kaggle/working/model_save/epoch_xx_xx.xx%.pth"
