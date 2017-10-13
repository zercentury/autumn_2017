# 目录
1. git
2. Windows Shell


## Git
> 配置好远程仓库后即可在本地创建一个新文件夹，并初始化为git本地仓库

```

git init # 初始化本地仓库

git clone '...'  # ... 为目标仓库的 SSH key 或  HTTPs url

# 对该仓库中的内容进行需要的修改，先add加入暂存区，再commit到当前分支中


git add . # . 代表当前目录下的所有（已修改）文件

git commit -m '修改信息摘要'  # commit到本地分支

# 修改完本地仓库后，即可以将修改的信息提交到远程仓库上

git remote # 查看远程库的信息

git push origin ... # ...代表着当前要提交的分支名称


# 另外在本地仓库操作时，涉及到多个分支的情况

git checkout ... # 从当前分支转移到...分支

# 查看分支历史

git log --oneline --graph --all

# 保持与原仓库的更新（Fork到自己的仓库中，无法保持更新）

git remote add upstream 原作者仓库地址

git remote update upstream

#rebase 操作之前一定要确保本地当前分之和上游分支一致
git rebase upstream/master 

```

> 更多git指令，请查看[Git 官方手册](https://git-scm.com/documentation)


## Windows Shell -- CMD
1. 目录操作命令 -- cd 、 md 、rd
2. 文件操作命令 -- dir、copy、del、ren
3. 通配符 -- ? 、 *
4. 快捷键

### 目录操作命令
1. cd（Change Directory）：改变当前目录
> 格式：cd 绝对/相对路径
> eg: cd C:\Users 

2. md（Make Directory）：建立子目录
> 格式：md 子目录名
>
> eg: md mmm

3. rd（Remove Directory）：删除子目录
> 格式：rd 子目录名
> 1. 只有空子目录才能被删除（除非添加 /S 强制删除）
> 2. 根目录和当前目录不能被删除
>
> eg: rd mmm

### 文件操作命令
1. dir : 文件目录清单
> 格式：dir 路径 [/P][/W] 
> /P : 分屏显示
> /W : 简要显示
>
> eg: dir E:\BaiduYun /P


2. copy: 复制文件
> 格式： copy 目标文件 目标路径
>
> eg: copy mm.txt E:\BaiduYun  

3. del: 删除文件
> 格式： del 文件名（当前目录下）
>
> eg: del mm

4. ren: 重命名文件
> 格式： ren 原文件名 新文件名

### 通配符
1. 问号（?）：匹配文件名中的任何一个字符
> mm? : mm1 mm2 mm3 ...
2. 星号（*）：匹配文件名中的零个或多个字符
> mm* : mm mm1 mm2 mm3 ...
>
> *.txt: mm.txt nn.txt ...
>
> g* : grape growth ...


### 快捷键（常用）

| 名称     | 功能                      |
| ------ | ----------------------- |
| F1     | 从左至右一个个字符地重复上次键入的命令     |
| F2     | 连续重复至某字符位置前所有字符（不含某字符）  |
| F3     | 复制上次输入的命令或当前光标后面剩余的全部字符 |
| F4     | 与 F2 相反删除到指定字符          |
| Del    | 删去当前位置字符                |
| Esc    | 清除当前行                   |
| Ctrl+C | 强行终止当前命令或程序的执行          |

Tips: 复制粘贴
> win10 CMD : 右键已执行行的目标文件名，自动paste到当前命令下
