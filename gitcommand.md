## git 基本命令 ##



 
-  git add 文件名/* --> 添加文件/全部文件到版本库（文件名需要加后缀）
-  git commit -m "版本信息" --> 提交本次修改
-  git log/git log --pretty=oneline/git log --oneline --> 查看提交信息/简洁版
-  git status --> 查看工作区状态
-  git reset -hard HEAD^ --> 版本回退上一级
-  git reflog --> 查看历史命令
-  git diff HEAD --> 查看区别
-  git checkout -b 分支名 --> 创建并切换到此分支
-  git checkout 分支名 --> 切换到当前分支
-  git branch 分支名 --> 创建分支
-  git branch --> 查看分支
-  git branch -d 分支名 --> 删除分支
-  git merge 分支名 --> 合并指定的这个分支到当前分支 
-  git remote add origin git@github.com:自己的github账户/文件夹.git --> 将本地库与远程库做关联
-  git push -u origin master --> 关联后第一次推送master分支的所有内容
-  git push origin master --> 将本地库的内容推送到远程库
-  git clone 远程库地址 --> 从远程库克隆到本地库

