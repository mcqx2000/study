git 远程协作
1.github简介 
2.git远程协作
（1）git clone 获取一个远程仓库
（2）git fetch 获取远程仓库中的所有分支和数据
（3）git pull
（4）git push   把本地的数据推送到远程仓库
len
下载安装git

打开 git bash
创建版本库    git init
git add readme.txt  把文件添加到仓库
git commit -m "wrote a readme file"  把文件提交到仓库
git log 查看历史记录（--pretty=oneline）
git reset --hard HEAD^
git reflog 记录每一次命令
git status 查看工作区状态
git diff HEAD --readme.txt  查看工作区和版本库里面最新版本的区别
git checkout --readme.txt  撤回工作区的修改

删除
git rm test.txt
git commit -m "rm test.txt"

创建SSH KEY
git clone     git@github.com:mcqx2000/demo.git
git push 

		
	git remote add origin git@github.com:mcqx2000/gitRepository.git
    git pull --rebase origin master
    git push -u origin master