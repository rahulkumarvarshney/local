#this project is my demo

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../A.pdf
        ../AI LAB.docx
        ../DOM MAnupl/
        ../EXECUTION.docx
        ../EXECUTIONCONTEXT.pdf
        ../Eclipse IDE for Enterprise Java and Web Developers - 2024-06.lnk
        ../FJDBC/
        ../HMARA JS/
        ../IMPORTANT INTERVIEW QUESTIONS.TXT
        ../MAHI/
        ../MongoDBCompass.lnk
        ../P.jpg
        ../RAHUL_RESUME.pdf
        ../RAT.pdf
        ../S.jpg
        ../TO-DO APP/
        ../UMS/
        ../Visual Studio Code.lnk
        ../XAMPP Control Panel.lnk
        ../apache-tomcat-10.1.26/
        ../chalopaper/
        ../code - Shortcut.lnk
        ../desktop.ini
        ../desktop/
        ../ecommerce_project/
        ../english wrata.txt
        ../english.pdf
        ./
        ../java6pm/
        ../jdbc/
        ../jdbcgla/
        ../mongoose code/
        ../ol/
        ../rahul - Chrome.lnk
        ../sql2024.txt
        ../th.jpg
        ../universty/
        ../~$2.docx
        ../~$AI LAB.docx
        ../~$ECUTION.docx
        ../~$HUL_RESUME.pdf
        ../~$MS LAB1.docx
        ../~$MS LAB2.docx
        ../~$aaaa.docx
        ../~$b2_assignment_23-sep.docx
        ../~$bdbms.docx
        ../~$color.docx
        ../~$hulvarshney.docx
        ../~$ms lab.docx
        ../~$mslab5.docx
        ../~$ocess state.docx
        ../~$port react.docx
        ../~$react.docx
        ../~$thon lab assignment_2384200161.docx

nothing added to commit but untracked files present (use "git add" to track)

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo (master)
$ cd dbs

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ ls
README.md

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ ls -a
./  ../  .git/  README.md

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

no changes added to commit (use "git add" and/or "git commit -a")

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git add index.html

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md


RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git add .

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html


RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git add .

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html


RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git commit -m "add new paragraph"
[main 77ea67c] add new paragraph
 2 files changed, 4 insertions(+), 1 deletion(-)
 create mode 100644 index.html

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 361 bytes | 361.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/rahulkumarvarshney/dbs.git
   8abdd9e..77ea67c  main -> main

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ cd dbse

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ cd ..

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ cd ..

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo (master)
$ cd dbs

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ git init
Reinitialized existing Git repository in C:/Users/RAHUL VARSHNEY/Desktop/gtdemo/dbs/.git/

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ ls
README.md  dbse/  index.html

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ ls -a
./  ../  .git/  README.md  dbse/  index.html

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ cd..
bash: cd..: command not found

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ cd ..

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo (master)
$ cd dbse
bash: cd: dbse: No such file or directory

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo (master)
$ cd dbse
bash: cd: dbse: No such file or directory

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo (master)
$ cd dbs

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs (main)
$ cd dbse

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ ls

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ ls -a
./  ../

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git init
Initialized empty Git repository in C:/Users/RAHUL VARSHNEY/Desktop/gtdemo/dbs/dbse/.git/

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ ls

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ ls -a
./  ../  .git/

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git add .

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git commit -m
error: switch `m' requires a value

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git commit -m "add new file"
[master (root-commit) 6d59640] add new file
 1 file changed, 11 insertions(+)
 create mode 100644 index.html

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git origin push
git: 'origin' is not a git command. See 'git --help'.

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'origin'

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'origin'

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git status
On branch master
nothing to commit, working tree clean

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git status
On branch master
nothing to commit, working tree clean

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git status
On branch master
nothing to commit, working tree clean

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git remote add origin https://github.com/rahulkumarvarshney/local.git

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git remote -v
origin  https://github.com/rahulkumarvarshney/local.git (fetch)
origin  https://github.com/rahulkumarvarshney/local.git (push)

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git branch
* master

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (master)
$ git branch -M main

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git branch
* main

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 382 bytes | 382.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/rahulkumarvarshney/local.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git push
Everything up-to-date

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git add .

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git commit -m "add css file"
[main 9a17786] add css file
 1 file changed, 3 insertions(+)
 create mode 100644 style.css

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/rahulkumarvarshney/local.git
   6d59640..9a17786  main -> main

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git add .

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git commit -m "add  readme file"
[main f5244e1] add  readme file
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/rahulkumarvarshney/local.git
   9a17786..f5244e1  main -> main

RAHUL VARSHNEY@LAPTOP-22919F4O MINGW64 ~/Desktop/gtdemo/dbs/dbse (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

RAHUL VARSH