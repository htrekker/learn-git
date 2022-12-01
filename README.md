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
