# <center>第一次技术报告</center>

### 1.Markdown

- **定义**:
> Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。

- **编辑工具**
个人喜欢[vscode](https://code.visualstudio.com/)，搭配插件“Markdown Preview Enhanced”，可分屏，一边编辑，一边即时显示效果。
效果如图：
![效果](http://upload-images.jianshu.io/upload_images/76130-cc41e78934f0fa32.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- **学习资源**
1.[typora Markdown Reference][1]
2.[Markdown 语法手册][2]

[1]: http://support.typora.io/Markdown-Reference/ "Markdown Reference"
[2]: http://blog.leanote.com/post/freewalk/Markdown-%E8%AF%AD%E6%B3%95%E6%89%8B%E5%86%8C "Markdown 语法手册 （完整整理版）"

### 2.GitHub

1) 官方入门指导：[GitHub Hello World](https://guides.github.com/activities/hello-world/ "Hello World · GitHub Guides")

2) GitHub 上工作流程
教程: <https://github.com/xirong/my-git/blob/master/git-workflow-tutorial.md>

3) GitHub 上 *fork* 后同步源更新的问题
有两种方法，
一、GitHub网站从源 pull request 到 fork 出的路径；
二，命令行法
```
git remote add upstream https://github.com/chenjun15/autumn_2017  # 替换为你的URL
git fetch upstream
git merge upstream/master
git push origin master
```
详见：<https://www.zhihu.com/question/20393785/answer/30725725>
