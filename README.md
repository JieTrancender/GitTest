1. 创建版本库 git init
2. 将工作区文件添加到暂存区 git add $fileName / git add .
3. 将暂存区文件提交到仓库 git commit -m "commitInformation]"
4. 查看仓库当前状态 git status
5. 查看仓库变化 git diff
6. 查看版本控制系统历史信息 git log / git log --pretty=onelien
7. 版本回退 git reset --hard HEAD^ (HEAD^表示上一个版本，HEAD^^表示上两个版本，HEAD~100表示上100一版本)
8. 查看命令历史 git reflog
9. 查看工作区文件和仓库文件区别 git diff HEAD -- $fileName
10. 撤销未添加到暂存区的修改 git checkout -- $fileName
11. 撤销已添加到暂存区但是未提交的修改到工作区 git reset HEAD $fileName
12. 删除文件 git rm $fileName
13. 创建SSH Key ssh-keygen -t rsa -C "your email"
14. 添加远程仓库 git remote add origin git@github.com:....
15. 将本地库内容推送到远程 git push -u origin master
16. 创建分支并切换到对应分支 git checkout -b $branchName / git branch $branchName & git checkout $branchName
17. 合并分支 git merge $branchName
18. 删除分支 git branch -d $branchName
19. 非Fast forward模式合并 git merge --no-ff -m "merge information" $branchName
20. 储藏当前工作区 git stash
21. 查看 & 回复工作区 git stash list & git stash pop
22. 指定本地非master分支与远程非master分支的链接 git branch --set-upstream $branchName origin/$branchName
23. 查看远程库信息 git remote -v
24. 创建标签 & 查看标签 & 对应提交创建标签 git tag v1.0 git tag git tag v0.923432423
25. 查看标签信息 git show v0.923432423
