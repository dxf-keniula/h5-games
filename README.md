## 项目初始化

```
# 克隆你的仓库到本地
git clone https://github.com/yourusername/your-repo-name.git
 
# 进入仓库目录
cd your-repo-name
 
# 检查gh-pages分支是否存在，该命令可以查看远程分支和本地分支
git branch -a
 
# 如果不存在gh-pages分支，创建gh-pages分支
git checkout --orphan gh-pages
 
# 添加所有静态文件到暂存区
git add .
 
# 提交更改
git commit -m "Initial gh-pages commit"
 
# 推送到GitHub的gh-pages分支
git push origin gh-pages
```

1、保证主页有index.html

2、孤立分支：`gh-pages`。整个项目唯一的分支，无master/main主分支

3、项目访问：`https://dxf-keniula.github.io/static-pages/index.html`