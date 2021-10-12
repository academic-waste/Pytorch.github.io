## 深入浅出Pytorch

You can use the [editor on GitHub](https://github.com/academic-waste/Pytorch.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Task01：PyTorch认知和安装

<!-- Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for
 -->
```markdown
Syntax highlighted code block

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
                
<!-- ## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/academic-waste/Pytorch.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out. -->
