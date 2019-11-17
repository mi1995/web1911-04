# git 的使用场景
1.分布是管理
2.多人协同配合
3.远程代码管理

## 本地源代码管理
1. 生成一个git本地仓库(一个项目只生成一次)
```shell
git init 

Initialized empty Git repository in E:/柠檬学院前端/阶四/1911-04直播/01/.git/
```

命令执行后 会在当前的工作目录里 生成一个隐藏的.git 目录  这个目录是当前项目的仓库文件夹 以后就不能删除这个目录了 删除后  这个代码记录就没了

2. 添加代码的变更列表
```shell
git add <文件路径|文件加路径>
```

3. 提交暂存（确认存储）
```shell
git commit -m "描述"
```

4. 查看分支
```shell
git branch
```

5. 创建分支
```shell
git branch <name>
```
在哪个分支上使用branch 创建分支 就是从这个分支上复制一个新的副本

6. 删除分支
```shell
git branch -D <name>
```

7. 切换分支
```shell
git checkout <branchName>
```



44444444444444444444444



