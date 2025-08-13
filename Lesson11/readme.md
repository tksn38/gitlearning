返回过去

git reset --hard HEAD
git reset --hard HEAD~
git reset --hard HEAD~n

PS E:\myweb> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   main.html

no changes added to commit (use "git add" and/or "git commit -a")
PS E:\myweb> 
PS E:\myweb> 
PS E:\myweb> git reset --hard HEAD #resetオプション使用前にbkすること！
HEAD is now at d9e8d69 55555
PS E:\myweb> 

PS E:\myweb> git reset --hard HEAD~  
HEAD is now at dd0d9b1 4444

PS E:\myweb> git log --oneline -6
d9e8d69 (HEAD -> master) 55555
dd0d9b1 4444
909b75c 333
fbe6d3d 22
3a764c9 1
5cf1810 modified. 202507051743
PS E:\myweb> 

PS E:\myweb> git reset --hard d9e8d69
HEAD is now at d9e8d69 55555
PS E:\myweb> 