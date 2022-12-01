# learn-git
用于学习git的仓库
# merge操作
考虑下面的一种情况：
```
  A---B---C topic
 /
D---E---F---G master
```
如果想要将topic分支merge到master分支。首先切换到master，在运行
```bash
git merge topic
```
完成后我们仍然在master下。
# pull
git pull = git fetch + git merge current-branch
考虑下面的情况：
```
  A---B---C master on origin
 /
D---E---F---G master
^
origin/master in your local repository
```
当前所在的分支为master，如果使用git pull，回导致将origin/master的变化拉取到本地，并且merge到本低master分支。
