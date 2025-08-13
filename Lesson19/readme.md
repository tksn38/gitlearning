git clone [url]
git remote -v
git push [origin] [master]

git clone

PS E:\myweb_github> git clone https://github.com/tksn38/test_20250705.git
Cloning into 'test_20250705'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.
PS E:\myweb_github> 
PS E:\myweb_github> dir

    Directory: E:\myweb_github

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----            2025/7/5    21:47                test_20250705

PS E:\myweb_github>

PS E:\myweb_github> cd .\test_20250705\
PS E:\myweb_github\test_20250705> 

PS E:\myweb_github\test_20250705> git remote -v
origin  https://github.com/tksn38/test_20250705.git (fetch)
origin  https://github.com/tksn38/test_20250705.git (push)
PS E:\myweb_github\test_20250705> 

git status
git branch -a
PS E:\myweb_github\test_20250705> git branch -a    
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/dev
  remotes/origin/main

PS E:\myweb_github\test_20250705> git branch dev remotes/origin/dev
branch 'dev' set up to track 'origin/dev'.
PS E:\myweb_github\test_20250705>
PS E:\myweb_github\test_20250705> git branch -a
  dev
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/dev
  remotes/origin/main

PS E:\myweb_github\test_20250705> git checkout dev   
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.
PS E:\myweb_github\test_20250705>

PS E:\myweb_github\test_20250705> git branch dev remotes/origin/dev
branch 'dev' set up to track 'origin/dev'.
PS E:\myweb_github\test_20250705>
PS E:\myweb_github\test_20250705> git branch -a
  dev
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/dev
  remotes/origin/main
PS E:\myweb_github\test_20250705> 
PS E:\myweb_github\test_20250705> git checkout dev   
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.
PS E:\myweb_github\test_20250705>

PS E:\myweb_github\test_20250705> git add .
PS E:\myweb_github\test_20250705> 
PS E:\myweb_github\test_20250705> git commit -m "added i love github.(dev_branch)"
[dev e089d8f] added i love github.(dev_branch)
 4 files changed, 26 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 index.html
 create mode 100644 main.html
 create mode 100644 style.css
PS E:\myweb_github\test_20250705>
PS E:\myweb_github\test_20250705> git status
On branch dev
Your branch is ahead of 'origin/dev' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS E:\myweb_github\test_20250705>
PS E:\myweb_github\test_20250705> 
PS E:\myweb_github\test_20250705> git remote -v
origin  https://github.com/tksn38/test_20250705.git (fetch)
origin  https://github.com/tksn38/test_20250705.git (push)
PS E:\myweb_github\test_20250705> 
PS E:\myweb_github\test_20250705> 


PS E:\myweb_github\test_20250705> git push origin dev
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 700 bytes | 350.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/tksn38/test_20250705.git
   0e50248..e089d8f  dev -> dev
PS E:\myweb_github\test_20250705> 


