#                                               技术报告



​                                  *by李禄马*

![头像](https://github.com/Luma123/liluma-/blob/master/touxiang/touxiang.jpg?raw=true"头像")

**我的[Github地址](https://github.com/Luma123)**

## 1.目录

> ​    (1).git

> ​    (2).Markdown

***

## 2.内容

###    (1).git

:	Git是一款免费、开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。

* Git是一个开源的分布式版本控制系统，可以有效、高速的处理从很小到非常大的项目版本管理。Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件。

* Torvalds 开始着手开发 Git 是为了作为一种过渡方案来替代 BitKeeper，后者之前一直是 Linux 内核开发人员在全球使用的主要源代码工具。开放源码社区中的有些人觉得BitKeeper 的许可证并不适合开放源码社区的工作，因此 Torvalds 决定着手研究许可证更为灵活的版本控制系统。尽管最初 Git 的开发是为了辅助 Linux 内核开发的过程，但是我们已经发现在很多其他自由软件项目中也使用了 Git。例如 很多 Freedesktop 的项目迁移到了 Git 上。

  ####  理解：

  * 1.git中同步的并不是直接仓库可视的东西，而是仓库中的.git隐藏文件。例如：我并没有用git rm命令删除文件（或git add添加文件），那么我发现本地可视的东西竟然比远程文件少（或多），这个时候你用git pull   或者git fetch命令，并没有发现改变，而且他竟然提示 Everything  up-to-date。原因就是远程仓库是和.git隐藏文件这个大脑进行同步的。并不是和可视化的库直接同步。
  * 2.要想你所做的东西得到肯定，就一定要执行 git commit文件，才能从暂存区提交到工作区，达成真正的更改。例如：git add 、git rm 等操作

  ***

  ### (2).Markdown

  :	Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。

* Markdown具有一系列衍生版本，用于扩展Markdown的功能（如表格、脚注、内嵌HTML等等），这些功能原初的Markdown尚不具备，它们能让Markdown转换成更多的格式，例如LaTeX，Docbook。Markdown增强版中比较有名的有Markdown Extra、MultiMarkdown、 Maruku等。这些衍生版本要么基于工具，如Pandoc；要么基于网站，如GitHub和Wikipedia，在语法上基本兼容，但在一些语法和渲染效果上有改动。

  ****

  #####                                                    代码框

  ​ 

```c++
include <iostream>

using   namespace   std;

int main ()

{

    return 0;

}
```

​	

####                                                表格：



| 姓名   | 是否在线 |
| ---- | ---- |
| 李禄马  | 在线   |



