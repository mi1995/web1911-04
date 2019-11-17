<<<<<<< HEAD:readme.md
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



2. 查询当前有哪些远程仓库
```shell
git remote 
```


4. 上传代码到远程仓库
git push <仓库名称> <分支名称>
```shell
git push github dev 
```

5. 绑定默认分支
git push -u <仓库名称> <分支名称>
```shell
# 第一次绑定
git push -u <仓库名称> <分支名称>

# 第二次绑定
git push 
```
=======
>>>>>>> 22:笔记.md
