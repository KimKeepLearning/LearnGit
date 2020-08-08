```markdown
初始化仓库
git init
文件添加至仓库
git add <file>
文件提交至仓库
git commit -m <message>
查看工作区状态
git status
查看修改的文件差异
git diff <file>
查看修改历史/所有指令
git log/reflog
回退版本
git reset --hard <commit id>/HEAD^
用版本库替换工作区版本
git checkout -- <file>
删除文件
rm <file>
git rm <file>
git commit
关联远程库
 git remote add origin git@github.com:KimKeepLearning/LearnGit.git
推送至远程库
git push -u origin master
```



```
新建并切换分支
git checkout -b <branch name>
= git branch dev
  git checkout dev
列出分支
git branch
合并指定分支到当前分支
git merge <branch>
```

