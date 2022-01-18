---
title: 使用 git 把内容推到 GitHub 上
---


1. 先在github或者码云上创建一个公开或私有项目：例如demo
2. 在本地也就是要推送的项目目录中使用 git init 进行初始化，把其变成git可以管理的仓库

```
git init
```

3. 若要忽略本地的文件或文件夹不被提交到git远程仓库 ，则需要在项目根目录下创建 .gitignore 文件
   touch .gitignore
4. 打开文件，编辑内容，写如要忽略的文件，例如：
   .idea # python中的一个隐藏文件，自动生成的，不需要提交
   *.py[cod] #一些没有用的附带文件，直接忽略即可
   按照上诉操作后，保存，那么这些文件就不会被提交了。

5. 将文件夹下所有文件从工作区保存到暂存区 git add .命令
   git add .
6. 把文件从暂存区提交到仓库区（本地的仓库） git-commit -m “此处写注释内容”
   git commit -m '注释内容'
7. 关联远程仓库 （第一次使用需要添加远程仓库的地址）
   git remote add origin git@git仓库的地址  
   #注意，此处的地址将https://省略
   注意，此处的地址将https://省略

或者

git remote add origin 你git仓库的地址

7. 将远程库与本地同步（如果远程仓库里面有文件等内容需要执行以下这一步）
   git pull --rebase origin master
8. 把本地内容推送到远程库 使用 git-push
   git push -u origin master
   按照上面的操作步骤就可以将本地文件推送到git远程仓库上了，并且可以自己设定不需要上传哪些文件。当然，情况因每人的配置环境或多或少出现问题，此教程只是解决众多问题中其中一个。