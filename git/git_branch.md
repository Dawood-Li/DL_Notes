## [Index](./git_index.md)
## Git Branch
### 分支 显示 本地
> git branch
### 分支 显示 远程
> git branch -r
### 分支 显示 所有
> git branch -a
### 分支 合并图
> git log --graph --decorate --all --oneline
### 分支 创建
> git branch [分支名]
### 分支 切换
> git checkout [分支名]
### 分支 创建并切换
> git checkout -b [分支名]
### 分支 合并
> git merge [分支名]
### 分支 删除 本地
> git branch -d [分支名]
### 分支 删除 远程
> git push origin --delete [分支名]
### 分支 推送本地仓库到远程仓库某分支
> git push [仓库名] [分支名]
### 分支 拉取远程分支
> git fetch
### 分支 拉取远程分支 并合并
> git pull
