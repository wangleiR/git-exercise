#### Git管理代码的版本
```
Git 是把数据看作是对小型文件系统的一组快照。
每次提交更新，或在 Git 中保存项目状态时，它主要对当时的全部文件制作一个快照并保存这个快照的索引。
为了高效，如果文件没有修改，Git 不再重新存储该文件，而是只保留一个链接指向之前存储的文件。
Git 对待数据更像是一个快照流。
```
#### 代码在Git 中都有哪些状态?
```
modified:  已修改 表示修改了文件，但还没保存到数据库中。
staged: 已暂存 表示对一个已修改文件的当前版本做了标记，使之包含在下次提交的快照中。
committed: 已提交 表示数据已经安全的保存在本地数据库中。
stashed: 储藏状态 可以获取工作目录的中间状态——并将它保存到一个未完结变更的堆栈中，随时可以重新应用。
```

#### Git的常用操作

- 新建本地代码库
```
git init
```
- 将代码库链接到远程仓库
```
git remote add pb git://github.com/paulboone/ticgit.git
```
- 提交代码到本地
```
git add .
git commit -m "comment"
```
- 提交代码的远程仓库
```
git push origin master
```
- 查看已暂存和未暂存的修改
```

git diff 
git diff --staged
```

fetch pull merge都表示什么

创建分支
合并分支

如何解决合并时候的冲突
git rebase 怎么用
git rebase vs git merge

如何修改已经提交的代码
如何将两次提交合并
如何调整提交的顺序

git bisect 怎么用？