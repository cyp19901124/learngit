this is read me
learngit

要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令git push -u origin master第一次推送master分支的所有内容；
此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；

改动后需要添加文件: git add filename
然后提交：	git commit -m "说明"
同步至服务器： git push origin master
