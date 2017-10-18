# rebase 为理解变基操作的实例
#git init
#echo "# rebase 为理解变基操作的实例" >> README.md
#vim .gitignore
#git add .
#git commit -m "初始化仓库"
#git push
#git branch i1
#git branch i2
#git checkout i1
#vim .gitignore
#git add .
#git commit -m "i1分支修改gitignore"
#git checkout i2
#vim .gitignore
#git add .
#git commit -m "i2分支修改gitignore"
#git checkout master
#git merge i1 i2
#修改gitignore冲突
#git add .
#git commit -m "解决冲突"
#git push
#git branch i3
#git branch i4
#git checkout i3
#vim .gitignore
#git add .
#git commit -m "i3分支修改gitignore"
#git checkout i4
#vim .gitignore
#git add .
#git commit -m "i4分支修改gitignore"
#git checkout master
#git rebase i3
#git rebase i4
#git push