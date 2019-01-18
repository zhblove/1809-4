### Git命令
1. 初始化命令：
git config --global user.name "Your Name"
git config --global user.email "email@example.com"
2. 初始化仓库
git init
3. 增加版本管理
git add filename
git commit -m '注释'
4. 仓库状态
git status
git diff
5. 版本回退
git log
git log --pretty=oneline
git reflog
git reset --hard HEAD^
git reset --hard 1094a
6. 工作区和暂存区/版本库
workspace:工作区
add：暂存区
commit:版本库
7. 删除命令
rm filename  本地删除
git rm filename 版本库删除
git checkout -- filename
8. 创建与合并分支
git checkout -b iwen
git branch 查看分支
git checkout iwen   切换分支
git merge iwen 合并分支
git branch -d iwen   删除分支
9. 关联远程仓库
> 1. 创建SSH
    ssh-keygen -t rsa -C "youremail@example.com"
> 2. Add SSH Key
> 3. 关联远程仓库
    git remote add origin https://github.com/Geekiwen/web1809.git
    git push
10. git忽略文件
    .gitignore