Gitでファイル操作
git add [file1 file2]
git add .
git rm
git mv
git rm --chached style.css
git status

PS E:\myweb> git commit -m "added style.css"
[master b5423ec] added style.css
 2 files changed, 4 insertions(+)
 rename index.html => index.htm (95%)
 create mode 100644 style.css

PS E:\myweb> git log
commit b5423ec4f1d0ae58979cdda895321e5c619f642e (HEAD -> master)
Author: tksn38 <tksn38@pekoro.moe>
Date:   Sat Jul 5 17:11:18 2025 +0900

    added style.css
    ...

PS E:\myweb> git log --oneline
b5423ec (HEAD -> master) added style.css
8fa2d90 added code:I love git!; added 1 line
c55807f added code:helo git
53ff1e1 create index.html
PS E:\myweb> 
PS E:\myweb> 
PS E:\myweb> dir 

    Directory: E:\myweb

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---            2025/7/5    17:09            334 index.htm
-a---            2025/7/5    17:08             15 style.css

PS E:\myweb>