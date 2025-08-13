git diff

PS E:\myweb> git diff  
diff --git a/index.html b/index.html
index a5fa805..b08fc26 100644
--- a/index.html
+++ b/index.html
@@ -9,5 +9,6 @@
 <body>
     Helo World!
     Helo Git!
+    I love git!
 </body>
 </html>
\ No newline at end of file

git add index.html
git diff --cached

PS E:\myweb> git diff --cached
diff --git a/index.html b/index.html
index a5fa805..b08fc26 100644
--- a/index.html
+++ b/index.html
@@ -9,5 +9,6 @@
 <body>
     Helo World!
     Helo Git!
+    I love git!
 </body>
 </html>
\ No newline at end of file
PS E:\myweb> 

PS E:\myweb> git add .
PS E:\myweb> 
PS E:\myweb> git commit -m "added code:I love git!; added 1 line"
[master 8fa2d90] added code:I love git!; added 1 line
 1 file changed, 1 insertion(+)
PS E:\myweb>
