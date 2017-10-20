# Part 1 工具安装

请在你的电脑上安装上 Anaconda 以及其自带的 Jupyter Notebook，Anaconda 是一个包含数据科学常用包的发行版本，同时也能够运行 Python 和通过 conda 进行一些管理。  
你可以参考 [这篇文档](https://millearninggroup.github.io/docs/anaconda-and-jupyter-notebook/) 来完成你的任务，也可以自行寻找自己认为合适的资源。  

具体要求：
1. 你需要学会在 Anaconda 上配置不同的虚拟环境，至少能在 python2.7 和 python3.5 版本之间熟练地切换，目前的作业我们使用的是 python2.7 版本，后面的作业将会切换到 python3.5 版本（甚至更高），注意推荐文档中提及的核心包一定要安装好；
2. 基于之前对 git 的学习，你需要学会熟练地通过命令行来使用 Anaconda；
3. 在这一部分，你可以不用先要求自己学会 Python，因为这正是后面的任务。

# Part 2 新的编程语言：Python

请确保你完成了 Part 1 的任务部分，因为这是 Part 2 部分的前提，至少你将会接触到一个十分有趣的交互式编程平台。的确，你也可以使用类似于 Pycharm 这样的 IDE ，但并不推荐你那样做。因为我们后续的作业将会以 Jupyter Notebook 支持的文件形式给出，你可以认为这是一种 Markdown + Python 的结合体。同样地，我们为你提供了一份 [参考文档](https://millearninggroup.github.io/docs/python/)。注意，官方文档往往起着字典的作用，当你对某一个函数作用不熟悉时，可以很方便地查询。（尤其是有中文文档的情况下）

具体要求：
1. 学会 Python 的基础语法；
2. 学会 Numpy 的基本数据处理套路，了解 Pandas 和 Matplotlib 的使用；

不要认为学习 Python 会是一个漫长的过程，你可以做的更好。  

另外，如果你完成了后面的任务，可以探索一下 Python 和这些包的更多用途。  

# Part 3 回归（理论部分）

- **VIDEO** Machine Learning (2017,Spring), 李宏毅，台湾大学
  - [Regression](http://www.bilibili.com/video/av10590361/)
  - [Where does the error come from?](http://www.bilibili.com/video/av10590361/#page=2)
  - [Gradient Descent](http://www.bilibili.com/video/av10590361/#page=3)

其他文本材料

- [各种距离](http://blog.csdn.net/shiwei408/article/details/7602324)
- [机器学习中的Bias(偏差)，Error(误差)，和Variance(方差)有什么区别和联系？](https://www.zhihu.com/question/27068705)
- [Why Data Scientists Split Data into Train and Test](http://info.salford-systems.com/blog/bid/337783/Why-Data-Scientists-Split-Data-into-Train-and-Test)
- [K折交叉验证评估模型性能](https://github.com/basicv8vc/Python-Machine-Learning-zh/blob/master/%E7%AC%AC%E5%85%AD%E7%AB%A0/ch6_section2.md)
- 一个介绍机器学习比较通俗化的系列文章
  - [写给大家看的机器学习书 第一篇](https://zhuanlan.zhihu.com/p/25328686)
  - [写给大家看的机器学习书 第二篇](https://zhuanlan.zhihu.com/p/25439997)
  - [写给大家看的机器学习书 第三篇](https://zhuanlan.zhihu.com/p/25358695)
  - [写给大家看的机器学习书 第四篇](https://zhuanlan.zhihu.com/p/25721582)



# Part 4 波士顿房价预测项目

在此项目中，我们将对为马萨诸塞州波士顿地区的房屋价格收集的数据应用本周学到的几个机器学习概念，以预测新房屋的销售价格。你首先将探索这些数据以获取数据集的重要特征和描述性统计信息。接下来，你要正确地将数据拆分为测试数据集和训练数据集，并确定适用于此问题的性能指标。然后，你将自己编写一个线性回归的模型，并使用不同的参数和训练集大小分析学习算法的性能图表。最后，你将根据一个新样本测试此模型并将预测的销售价格与你的统计数据进行比较。  

作业文件：boston_housing/boston_housing.ipynb  

如果你完成了前面的任务，你应该知道 boston_housing.ipynb 是一个什么样的文件。  

（本项目作业修改自 [Udacity Machine Learning Nanodegree Project](https://github.com/nd009/boston_housing)）



# 注意

学习过程中，如果觉得持续时间太长无法集中注意力，不妨劳逸结合放松一下。如果你对某个学习资料不能第一时间看懂，可以考虑通过网络解决你心中的疑惑。如果你觉得你找到了一篇很好的补充材料，欢迎分享给大家。  

如果想要提问，请使用 Github 的 issue 板块，在线私聊提问的确不是什么高效的解决问题的方式（除非你确定对方能够直接有效地解决你的问题）。不要羞于暴露你在某一方面的疑惑，或许你提的某一个问题会很有讨论价值。