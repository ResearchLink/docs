# docs
## 提代码流程

1. 创建分支
2. 在新分支上修改代码
3. ``git fetch origin master`` and ``git rebase origin/master``
4. ``git push origin local_branch:remote_branch``
5. 修conflicts，并把没有错误的代码提pull request
6. 自己merge到master
7. 删除原branch
8. ``git checkout master``, ``git pull``
9. 从1开始循环

## commits命名规则
1. 新特性：fea/[描述]
2. debug： fix/[描述]
3. 其他的待补充
