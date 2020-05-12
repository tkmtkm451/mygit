初始化项目
git init

关联远程项目
git remote add oragin 项目地址

第一次发布项目(本地-远程)
git add .   //当前目标文件存到暂存区
git commit  -m "注释内容"  //暂存区-本地分支(默认master)
git push -u oragin master //将项目推送到远程 第一次提交将分支推送到远程master分支

提交
git add 
git commit -m "注释"
git push oragin master