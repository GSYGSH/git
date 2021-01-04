git checkout xxx  用暂存区文件覆盖当前工作区
git rm --cache xxx 删除暂存区文件，但工作区文件会保留

git reset --hard ID 回退版本

git checkout -b xxx 开展分支并切换到该分支
git branch 查看分支
git branch xxx 创建分支
git branch -d xxx 删除某分支，注意：该分支已经合并过才可以使用
git branch -D xxx 强制删除分支
git merge xxx 合并某分支

git rm origin 
git add remote xxx xxx //更改仓库地址

git add remote 仓库名 仓库地址  //给仓库起别名
git push 仓库名 分支名  //推动到远程仓库,-u可以记住仓库和分支，下次就直接git push
git pull 仓库名 分支名  //拉取最新版本


git stash //将没有commit的东西暂时保存提交，形成一个干净的工作区
git stash pop //将原来工作区还原