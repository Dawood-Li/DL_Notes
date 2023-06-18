## [Index](./git_index.md)

### git rm
> git rm 不再纳入版本管理 (但commit历史还在)  

### rm
> rm 在工作目录被剔除  
> 需要git add 或者git commit -a来同步这次更改 最终效果同上  

### git mv
> git mv 新文件将会继承文件的修改历史 (但commit历史还在)  

### mv
> mv 新文件不继承文件修改历史 (但commit历史还在)

### 综上
> 永远使用git mv 和 git rm 这样会保存记录 

