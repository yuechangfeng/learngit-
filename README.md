3 learngit 
如果在本地空文件创建项目
$ git init //创建 Git
echo 文本内容 >> README.md
git add file 
git commit -m xx
git branch -M mian //创建主分支
$ git branch -a //查看分支
$ git remote add origin git@xx:xx/xx/.git //添加远程仓库地址
$ git push -u origin main //将 远端仓库也会新建一个分支main，并将刚关联远端origin的本地仓库推送到远端仓库
在github的站点上查看具体情况
