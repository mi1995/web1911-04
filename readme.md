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


<<<<<<< HEAD
=======
6. 删除分支
```shell
git branch -D <name>
```

7. 切换分支
```shell
git checkout <branchName>
```

8. 合并分支
```shell
git merge <otherBranch>
```
9. 配置参数
```shell
# --golbal 可以不写  以后每次创建仓库需要再配置一遍
# --golbal 加上后 以后的所有项目默认用这个参数
git config --golbal use.email "填入你的邮箱地址"
git config --golbal use.name "填入你的名字"
```
>>>>>>> dev

-----------------------------------------------------
## 远程仓库
1. github 这个免费托管代码的网站
[github] (https://github.com/)

支持两种模式的仓库
-public 每个人都可以访问 和复制  不可以修改
-private 未经过允许的用户不能访问 和复制 以及修改
2. gitlab 需要自己公司搭建
3. 阿里云 腾讯 收费的私有仓库
4. gitee 码云 免费

1. 在本地添加一个远程仓库的地址
git remote add <仓库名称> <仓库地址>
```shell
git remote add github https://github.com/mi1995/web1911-04.git
# github 是仓库名
# https://github.com/mi1995/web1911-04.git 是仓库地址
```

2. 查询当前有哪些远程仓库
```shell
git remote 
```

3. 删除远程仓库
git remote remove <仓库名称>
```shell
# 例：
git remote remove github
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
