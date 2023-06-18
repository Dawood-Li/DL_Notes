## [Index](./git_index.md)

# 1.

## 分布式版本管理系统

### 三种状态
* 已提交  
* 已修改  
* 已暂存

### 三个分区
* 工作目录  
* 暂存区  
* git目录  

### 三种操作
* 工作目录 -> 暂存区
> add  
* 暂存区   -> git目录
> commit  
* git目录  -> 工作目录
> checkout  

### git 三种使用方式
* 命令
* gui
* ide插件


## 远程仓库基础
### 1. 克隆
> git clone https://github.com/xxx/xxx
### 2. 查看库关联的所有远程服务器
> git remote
### 3. 所有远程仓库的所有分支 /多人协作
> git remote -v
### 4. 添加协作仓库
> git remote add [你希望的仓库简称] [仓库地址]
### 5. 拉取代码
> git fetch [仓库]  
> git merge [仓库] [分支]  
> git pull  
* pull = fetch + merge  
* fetch会更新所有分支 但pull只会更新当前分支  
* 建议使用fetch + merge而不是pull 除非确定会自动合并成功
### 6. 推送仓库
> git push [仓库] [分支]  
* 推送前先拉取
* 推送前先git status 查看即将发生的变更







* checkout命令

git init --bare 
裸仓库 指不含工作区的git目录

