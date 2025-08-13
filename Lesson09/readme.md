Git ignore管理

.gitignore　※サブフォルダー含め、該当ファイルを管理外にする。

PS E:\myweb> dir

    Directory: E:\myweb

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---            2025/7/5    17:21              0 .gitignore
-a---            2025/7/5    17:09            334 index.htm
-a---            2025/7/5    17:13             15 style.css
-a---            2025/7/5    17:20              0 test.tmp

PS E:\myweb> 

PS E:\myweb> type .gitignore
#.gitignore
*.tmp
PS E:\myweb> 
PS E:\myweb> 

PS E:\myweb> dir

    Directory: E:\myweb

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----            2025/7/5    17:27                subdir
-a---            2025/7/5    17:23             18 .gitignore
-a---            2025/7/5    17:09            334 index.htm
-a---            2025/7/5    17:13             15 style.css
-a---            2025/7/5    17:20              0 test.tmp

PS E:\myweb> 
PS E:\myweb> git commit -m "added subdir"   
[master 372dcc7] added subdir
 2 files changed, 3 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 subdir/my.css
PS E:\myweb>
PS E:\myweb> git status
On branch master
nothing to commit, working tree clean
PS E:\myweb>

