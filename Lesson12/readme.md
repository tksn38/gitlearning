git reflog [-n num]
git reset --hard [commit_id]

PS E:\myweb> git log --oneline -6
d9e8d69 (HEAD -> master) 55555
dd0d9b1 4444
909b75c 333
fbe6d3d 22
3a764c9 1
5cf1810 modified. 202507051743
PS E:\myweb> 

PS E:\myweb> git reflog -3
fbe6d3d (HEAD -> master) HEAD@{0}: reset: moving to HEAD~3
d9e8d69 HEAD@{1}: reset: moving to d9e8d69
fbe6d3d (HEAD -> master) HEAD@{2}: reset: moving to HEAD~2
PS E:\myweb> 
PS E:\myweb> git reset --hard d9e8d69
HEAD is now at d9e8d69 55555
PS E:\myweb>
PS E:\myweb> git log --oneline -6    
d9e8d69 (HEAD -> master) 55555
dd0d9b1 4444
909b75c 333
fbe6d3d 22
3a764c9 1
5cf1810 modified. 202507051743
PS E:\myweb> 