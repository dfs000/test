## git本地初始化

```
#本地初始化
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/dfs000/test.git
git push -u origin main
```

## **将本地dev分支代码提交到远程dev分支**

(1)git branch --set-upstream-to=origin/feature/dev feature/dev // 将本地feature/dev分支与远程feature/dev分支关联起来

(2)git pull // 拉取远程分支代码

(3)git push // 推送远程仓库

## git clone 指定分支

git clone -b dev_jk http://10.1.1.11/service/tmall-service.git

$ git pull origin master          # 将远程仓库里面的项目拉下来

$ dir                        # 查看有哪些文件夹

$ git rm -r --cached target       # 删除target文件夹
$ git commit -m '删除了target'    # 提交,添加操作说明