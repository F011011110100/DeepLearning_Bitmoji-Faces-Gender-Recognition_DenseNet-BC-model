# DeepLearning_Bitmoji-Faces-Gender-Recognition_DenseNet-BC-model

### 深度学习作业——Kaggle比赛——Bitmoji Faces Gender Recognition——运用DenseNet-BC模型
- 在Kaggle的notebook中运行，直接添加Kaggle比赛中的数据集，代码中路径设置为了Kaggle上的路径。
- 运用GPU进行训练。
- 在读取权值的这一步：每次运行产生的文件都不一样，此处需要改变
> weight_filepath = "/kaggle/working/model_save/epoch_xx_xx.xx%.pth"
- 由于文件过于庞大。如需查看每一次迭代所训练的权值，请访问：https://www.kaggle.com/code/fengjiayi/faces-recognition-v2/data
中的output/model_save文件夹下的内容

### Deep Learning Assignment -- Kaggle Competition -- Bitmoji Faces Gender Recognition -- using DenseNet-BC model
- Run in Kaggle's notebook, directly add the data set from the Kaggle contest, and set the path in the code to the path on Kaggle.
- Use GPU for training.
- In this step of reading weights: Each run produces a different file, which needs to be changed here
> weight_filepath = "/kaggle/working/model_save/epoch_xx_xx.xx%.pth"
- Because the file is too large. If you want to view the training the weights of each iteration, please visit: https://www.kaggle.com/code/fengjiayi/faces-recognition-v2/data
In the output/model_save folder
