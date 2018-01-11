# GitHub的学习
之前通过网上碎片化的学习了一段时间的github，还将笔记用txt上传了上来，现在看来，真的是丑得一逼啊！！！原来还是README.md的文档漂亮。

上了年纪了，所以记东西还得靠笔记啊～～～

这次借托管一个Modbus-RTU的软件来回顾一下github的使用吧。

## 回顾
1. git init 创建一个git仓库在本地
2. 当我们在本地仓库中，添加了文件后，我通过.gitignore文件来管理需要忽略的文件，个是就是*.ini或者具体文件 a.ini。如果是需要忽略整个文件夹则  file/
3. 通过README.md文档来描述项目
4. git add .表示全部提交到暂存区
5. git commit -a -m "备注" -a表示关注的文档，有修改的全部都提交到仓库
6. git status 查看状态
7. git log --oneline  查看版本情况
8. git reflog 查看自己版本操作的指令
9. 需要push到远程仓库时，需要在远程端线建立一个仓库，比如建立一个远程仓库aaa.git 那么可以通过 git remote add origin git@github.com:hechao17/aaa.git  关联到远程仓库
10. 第一次push到远程仓库使用 git push -u origin master
11. 以后每次提交只需要 git push origin master
12. 当然我们也可以克隆别人的仓库到本地，git clone [url] [本地name] 这样将会在自己的本地目录建立一个 **本地name** 的文件夹。


## 新知识
#### 关于README.md
1. `![](https://github.com/hechao17/Modbus-RTU/raw/master/md_pic/wechat.png)`在README.md中添加一张图片的方法` ![](xxx)` xxx表示网址，我们可以引用网站的图片地址，也可以使用上传到github中，比如实例中，我们hechao17是我的github，Modbus-RTU是项目名称，在这个项目中有一个文件夹md_pic，我们引用了wechat.png这张图片。
2. `<br>`用于普通的文本的换行
3. 应用一个连接 [阿莫电子论坛](https://www.amobbs.com "打开论坛")，操作`[阿莫电子论坛](https://www.amobbs.com "打开论坛")`


----------
![](https://github.com/hechao17/Modbus-RTU/raw/master/md_pic/wechat.png)

Email: he-128@163.com

Q Q : 357407542

----------



