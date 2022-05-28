Git is a version control System
Git is a free software distribute under the GPL
修改
Git 命令：
git add file 添加文件
git diff 文件比较
git commit -m comment 文件提交
git status 文件状态
git reset --head HEAD^ 回到上一个版本HEAD^^上上个版本，100个版本 HEAD~100
git reset --head 版本的id 回到对应的版本
git reflog 记录每次的命令
第一次修改
git checkout -- file 撤销操作
git remote add origin git@github.com:ZWeiMin/learngit.git 关联远程库
把本地库推送道远程公共库GitHub
git put origin master 本地提交
git remote -v 查看远程库信息
git remote rm origin 删除远程库，非物理删除
git push -u origin master第一次推送master分支的所有内容
