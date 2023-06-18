## [Index](./git_index.md)

## git remote

### 克隆远程仓库
> git clone [仓库url]  
> 仓库默认别名是origin

### 查看仓库服务器名
> git remote
> > origin  

### 查看仓库服务器分支
> git remote -v
> > origin  https://github.com/schacon/ticgit (fetch)  
> > origin  https://github.com/schacon/ticgit (push)  


### 查看远程仓库详情
> git remote show [仓库]


### 添加另一个远程仓库并起别名
> git remote add [仓库别名] [仓库url]

### 修改仓库别名
> git remote rename [旧名] [新名]

### 删除一个远程仓库
> git remote remove paul

### 拉取代码
> git fetch [仓库]/[分支]

### 推送代码
> git push [仓库] [分支]
> 1. 必须拥有写权限  
> 2. 必须先fetch再push  

