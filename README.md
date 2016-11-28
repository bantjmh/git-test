# Git Note

###查看文件日志记录
	git log Hello.java 
	git log --pretty=oneline 

###添加并提交
	git commit -a -m "comment" 

###查看文件差异
	git diff Hello.java

###回退
	git checkout Hello.java	//未添加&未提交 
	git reset HEAD Hello.java	//已添加&未提交
	git reset --hard HEAD~1		//已添加&已提交  回退到上一个版本
	git reset --hard 41dea12	//回退到指定版本

###分支
	
