# 1.前沿
对于git内容学习整理。
# 2.基础内容
## 2.1 本地创建
### 2.1.1  git init 
生成了.git目录，对于文件、指针等进行存放。

## 2.2 添加文件、文件夹
### 2.2.1 git add filename
执行上面的命令，没有任何显示，这就对了，Unix的哲学是“没有消息就是好消息”，说明添加成功。
支持保存到了暂存区。

![git-add-2](jpg\git-add-2.jpg)

### 2.2.2 git commit -m "comment"

对于放到暂存区的变动进行提交。

![git-commit](jpg\git-commit.jpg)

1个文件变动了，2个insert。

### 2.2.3 git status 查看状态

查看状态，对于之前的readme.txt文件修改其中一行的内容。
此时执行```git status```：

![git-status](jpg\git-status.png)

显示了“modified: readme.txt”，并且提示了没有增加到暂存区。



### 2.2.4 git diff

展示和之前的不同：

![git-diff](jpg\git-diff.jpg)

可以看到，在1-2行的时候，出现了差异。



### 2.2.5 再次提交 

修改readme文件之后，可以看到，git提示将要提交的是readme.txt文件，然后commit：

![git-commit-2](jpg\git-commit-2.jpg)

