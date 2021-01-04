# git 笔记

## 1.基础

### 1.1本地创建git版本库

​			git-->bash here-->输入:git init

### 1.2更新变更到版本库

> 添加到暂存区

​		git add [文件名]  或者 git add .

​		.  表示全部

> 提交到本地版本库

​		git commit -m "提交的信息"

![git提交流程图-本地](gitNotePicture\git提交流程图-本地.jpg)

![git提交成功状态](gitNotePicture\git提交成功状态.jpg)



### 1.3撤销修改

> 仅保存,未添加到暂存区,撤销修改
>
> > git restore <fileName>
> >
> > > 回到上次版本库的状态

> 已添加到暂存区,撤销修改
>
> > git restore --staged <fileName> 
> >
> > > 将暂存区的修改回退到工作区,变为未添加状态
> > >
> > > > 再次执行第一步,即可回退到上个版本库版本



### 1.4  删除文件





