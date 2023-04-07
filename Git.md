**Git初始化&远程推送**

- git init #创建本地仓库

- git add . #添加所有文件

- git add somefile #添加某一个文件

- git commit -m ‘第一次提交’ #将文件添加到仓库

- git remote add origin git@github.com?*****/configserver.git #连接仓库

- git push origin master #将本地代码提交到远程仓库

  如果报上面的错误的话，先执行git pull --rebase origin master，

  再执行 git push origin master

  其他：git status #查看状态
