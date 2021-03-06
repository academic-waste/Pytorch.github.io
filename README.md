# 深入浅出Pytorch 
Learn Pytorch with DataWhale


# Pytorch的诞生
2017 年 1 月，FAIR（Facebook AI Research）发布了 PyTorch。PyTorch 是在 Torch 基础上用 python 语言重新打造的一款深度学习框架。
Torch 是采用 Lua 语言为接口的机器学习框架，但是因为 Lua 语言较为小众，导致 Torch 学习成本高，因此知名度不高。
#Pytorch实现模型训练的五大因素
- 数据：包括数据读取，数据清洗，进行数据划分和数据预处理，比如读取图片如何预处理及数据增强。
- 模型：包括构建模型模块，组织复杂网络，初始化网络参数，定义网络层。
- 损失函数：包括创建损失函数，设置损失函数超参数，根据不同任务选择合适的损失函数。
- 优化器：包括根据梯度使用某种优化器更新参数，管理模型参数，管理多个参数组实现不同学习率，调整学习率。
- 迭代训练：组织上面 4 个模块进行反复训练。包括观察训练效果，绘制 Loss/ Accuracy 曲线，用 TensorBoard 进行可视化分析。
# Pytorch的安装
- 数据：在anaconda中创建环境
- 在terminal中运行 conda install pytorch torchvision -c pytorch
- 检查是否安装成功 >>> import torch
                >>> print(torch.__version__)
