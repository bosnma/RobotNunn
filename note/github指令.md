Nunn的学习笔记
=====================================================================
git相关指令
---------------------------------------------------------------------
####git diff
列出文件差别
####git add
添加文件     git add . 通配所有，提交所有    add之后变成可提交状态，commit才有效
####git commit -m""
把add过的文件提交到本地库，
####git status
可以确认哪些被提交，哪些不会被提交
####git push
推到远程端去
####git pull
拉取
####git add -u
Bosn said：就是把要删除的文件/文件夹也提交上去-默认是不带删除的。。。其实我也没太懂为什么要这么搞- -可能你add的时候都是修改、新增的文件。但是被删除掉的，你add后面的路径都不知道写啥。所以区分开把。
###ls
查看文件夹
###以下是绑定本机ssh
####ssh-keygen -t rsa -C "your_email@youremail.com"
这个这个指令是获取本机的keygen，根据提示输入内容
####ssh -T git@github.com
在github的SSH中添加了刚刚导出的pub文件内容之后，测试是否通过
####git config --global user.name "your name"
输入本机显示的用户名
####git config --global user.email "your_email@youremail.com"
输入本机显示的邮箱
