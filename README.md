# hello-world
study account for study github

## Repository
A repository is the basic unit of GitHub, most commonly **a single project**. 

## Issue
An Issue is **a note** on a repository about something that **needs attention**.

## Branch
Branching is the way to work on different parts of a repository at one time.![](https://guides.github.com/activities/hello-world/branching.png)
[Branching from wiki](https://en.wikipedia.org/wiki/Branching_(revision_control))

## Commit
On GitHub, **saved changes** are called commits.

## Workflow
1. first create an brance
2. pull request

## Folk a repo [在Github和Git上fork之简单指南](http://linux.cn/article-4292-1-rss.html)
A fork is a copy of a repository. **Fork** is in the GitHub context, doesn't extend Git.
### fork并且更新一个仓库
现在有这样一种情形：有一个叫做Joe的程序猿写了一个游戏程序，而你可能要去改进它。并且Joe将他的代码放在了GitHub仓库上。下面是你要做的事情：
![](https://dn-linuxcn.qbox.me/data/attachment/album/201411/24/162415ki4zz0z7zy14zv3y.png)

1. **Fork他的仓库：**这是GitHub操作，这个操作会复制Joe的仓库（包括文件，提交历史，issues，和其余一些东西）。复制后的仓库在你自己的GitHub帐号下。目前，你本地计算机对这个仓库没有任何操作。
2. **Clone你的仓库：**这是Git操作。使用该操作让你发送"请给我发一份我仓库的复制文件"的命令给GitHub。现在这个仓库就会存储在你本地计算机上。
3. **更新某些文件：**现在，你可以在任何程序或者环境下更新仓库里的文件。
4. **提交你的更改：**这是Git操作。使用该操作让你发送"记录我的更改"的命令至GitHub。此操作只在你的本地计算机上完成。
5. **将你的更改push到你的GitHub仓库：**这是Git操作。使用该操作让你发送"这是我的修改"的信息给GitHub。Push操作不会自动完成，所以直到你做了push操作，GitHub才知道你的提交。
6. **给Joe发送一个pull request：**如果你认为Joe会接受你的修改，你就可以给他发送一个pull request。这是GitHub操作，使用此操作可以帮助你和Joe交流你的修改，并且询问Joe是否愿意接受你的"pull request"，当然，接不接受完全取决于他自己。

### 同步一个fork
Joe和其余贡献者已经对这个项目做了一些修改，而你将在他们的修改的基础上，还要再做一些修改。在你开始之前，你最好"同步你的fork"，以确保在最新的复制版本里工作。下面是你要做的：
![](https://dn-linuxcn.qbox.me/data/attachment/album/201411/24/162416icr0h6wzr6ec2jze.png)

![](http://i.stack.imgur.com/yPKXU.png)
