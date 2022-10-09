## git 操作

### 核心操作

1. 将代码提交到本地仓库

- 提交到暂存区 git add . 将目录下所有的文件添加到暂存区
- 提交到本地仓库 git commit -m 'commit message'

2. 将本地仓库同步到远程仓库

- 建立本地仓库和远程仓库的链接 git remote add 远程仓库的小名(origin) 远程仓库的地址(https/ssh)
- 推送代码 git push
  - 第一次推送新分支代码的时候 git push -u 远程仓库的小名(origin) 本地分支名:远程分支名
    如果说本地分支名和远程分支名一样, 可以省略 eg: git push -u origin master

### 杂项

// 2. git log
// - 查看 commit 记录
// - 查看有一条 commit 记录, 是 vue 帮我们初始化的

// 3. git status
// - 查看当前 git 仓库状态

// 4. git add . 将所有文件添加的暂存区

// 5. git commit -m''
// - 将文件提交到本地仓库

// 6. git remote add origin 仓库地址
// - 建立本地仓库和远程仓库的链接

// 7. git remote -v
// - 查看当前仓库关联的远程仓库, 显示你给远程仓库起的小名还有远程仓库的具体地址

// 8. git push -u origin 本地分支名:远程分支名
// - 推送代码到远程仓库指定分支
// - 如果本地分支名和远程分支名相同可以省略

// 9. 创建并切换分支
// - git checkout -b 分支名

// 10. 查看分支
// - git branch

// 11. 切换分支名
// - git checkout 分支名

