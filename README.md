# git 使用流程

## 常用指令介绍

| 操作                         | 指令                                            |
| :--------------------------- | :---------------------------------------------- |
| 克隆远程仓库                 | git clone <git链接>                             |
| 切换分支                     | git checkout <分支名>                           |
| 创建新分支并绑定远程分支     | git branch --track <新分支名> <远程分支名>      |
| 添加upstream仓库             | git remote add upstream <git链接>               |
| 同步远程分支                 | git rebase <远程主机名> <远程分支名>            |
| 查看当前版本状态（是否修改） | git status                                      |
| 显示所有未添加至缓存的修改   | git diff                                        |
| 将该文件添加到缓存           | git add <文件路径>                              |
| 提交                         | git commit -m ‘提交信息’                        |
| 合并上一次提交并重设提交信息 | git commit --amend -m ‘提交信息’                |
| 将 add 和 commit 合为一步    | git commit -am ‘提交信息’                       |
| 查看提交日志                 | git log                                         |
| 显示所有分支                 | git branch -a                                   |
| 上传代码                     | git push <远程主机名> <本地分支名> <远程分支名> |

## 场景

### 基本流程

- [搭建 git 环境](repo.md)
- [提交代码流程](commit_steps.md)

### 常见问题及解决

- 合并多个提交
- 解决冲突
