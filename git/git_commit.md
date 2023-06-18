## [Index](./git_index.md)

## git commit

### 未跟踪/已修改 -> 已暂存
> git add

### 已暂存 -> 已修改
> git reset HEAD <file>

### 已暂存 -> 已提交
> git commit

### 自动暂存已修改的文件
> git commit -a

### 补交
> git commit --amend

### 清空暂存区
> git reset  

### 清空暂存区同时恢复工作目录
> git reset --hard

### 临时存储工作目录
> git stash pop  
> git stash push

### 任何已提交的东西都可以恢复
