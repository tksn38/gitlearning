ブランチ間の競争を起こす

git checkout -b [branch_name]

git checkout -b dev
nano index.html

git add.
git commit -m "modified by dev."
git checkout master
nano index.html

git add.
git commit -m "modified by master."

git merge dev

PS E:\myweb> git merge dev
Auto-merging index.html
CONFLICT (content): Merge conflict in index.html
Automatic merge failed; fix conflicts and then commit the result.