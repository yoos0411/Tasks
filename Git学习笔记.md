# Git学习笔记
## 第一次 Git 完整提交流程
1. 在本地新建文件夹，进入目录，创建 hello.md，写入内容：`# Hello刘洪志`
2. 初始化本地仓库
git init
3. 将文件加入暂存区
git add hello.md
4. 提交到本地仓库
git commit -m "add hello.md"
5. 复制仓库链接
6. 关联远程仓库
git remote add origin 仓库地址
7. 首次推送
git push -u origin main
