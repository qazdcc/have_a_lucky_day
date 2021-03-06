#### 1.git 常用命令：

| 命令                       | 介绍及用法                                                   |
| -------------------------- | :----------------------------------------------------------- |
| git init                   | 创建一个新的git管理仓库                                      |
| git add xxx                | 将xxx文件添加到**本地仓库中**                                |
| git commit -m "xxx"        | 将当前仓库中的所有commit文件提交到**本地仓库中**，-m为提交的备注， <br/> 类似svn commit -m 'xxx' |
| git status                 | 查看当前本地仓库的修改情况，当前的状态<br/>有点类型svn st    |
| git diff xx                | 查看xx文件的修改情况，<br>类似svn diff                       |
| git log                    | 令显示从最近到最远的提交日志，我们可以看到3次提交            |
| git reset --hard HEAD^     | 回退版本 一个^代表回退前一个                                 |
| git reflog                 | 查看命令历史，以便确定要回到未来的哪个版本                   |
| git checkout -- readme.txt | 把`readme.txt`文件在工作区的修改全部撤销 <br>类似svn revert xx，就是将所有修改回退 |
| git rm xxx                 | 在git管理下删除xxx；类似svn delete xx                        |
|                            |                                                              |
| **远程仓库** github        |                                                              |
| git remote add origin xxx  | 当当前分支连接到远程仓库xxx中，xxx在github中可以看到         |
| git push -u origin master  | 把本地库的内容推送到远程，用`git push`命令<br>实际上是把当前分支`master`推送到远程 |
| git clone                  | 拉一个自己的分支，类似svn cp A a，a为自己的分支              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |
|                            |                                                              |



### 2.git关于工作区、缓冲区、master的理解

https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/0013745374151782eb658c5a5ca454eaa451661275886c6000

使用git add将工作区的修改保存到缓冲区，使用git comiit将缓冲区的修改保存到master分支