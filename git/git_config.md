## [Index](./git_index.md)

## git config

### 查看配置
> git config --list  
> git config --list --show-origin  

### 配置git
> git config --system // 针对系统  
> git config --global // 针对当前用户  
> git config --local  // 针对当前文件夹  

### 设置用户
> git config --list // 查看配置
> git config --global user.name "dawood li"  
> git config --global user.email dawood_li@outlook.com  
> git config --global core.editor emacs 设置默认编辑器？  

### 署名
> git config --global user.name "Dawood-Li"  
> git config --global user.email "dawood_li@outlook.com"  

### 默认编辑器 用于处理冲突
> git config --global core.editor code
