##王爱林的工作平台##

##资料##
https://spring.io/guides
https://spring.io/guides/gs/serving-web-content/

##工具##
https://github.com/

##Github push##
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ailinwang0501/MyPlatform.git
git push -u origin master

##说明##

git init                  //初始化代码仓库
git add learngit.txt      //把所有要提交的文件修改放到暂存区
git commit -m 'add a file'//把暂存区的所有内容提交到当前分支
git status                //查看工作区状态
git diff                  //查看文件修改内容
git log                   //查看提交历史
git log --pretty=oneline  /单行显示
git reset --hard HEAD^　　 //回退到上一个版本，其中（HEAD^^(上上版本),HEAD~100(往上100个版本)）

commit id        //(版本号) 可回到指定版本
git reflog       //查看历史命令git 

工作区（Working Directory）
版本库（Repository） #.git
stage(index) 暂存区
master Git自动创建的分支
HEAD 指针
git diff HEAD -- <file> //查看工作区和版本库里最新版本的区别
git checkout -- <file>  //用版本库的版本替换工作区的版本，无论是工作区的修改还是删除，都可以'一键还原'
git reset HEAD <file>   //把暂存区的修改撤销掉，重新放回工作区。
git remote rm <file>           //删除文件，若文件已提交到版本库，不用担心误删，但是只能恢复文件到最新版本
