

$ git init

hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /home/green/Desktop/Magnun Opus/the gym/git projects/bundle 1/exercise 1/.git/
 
$ git branch -m main
 
$ touch README.md
 
$ ls
 
index.html  README.md
 
$ git add .
 
$ git commit -m "bundle version 1.1"
 
[main (root-commit) f9aead7] bundle version 1.1
 2 files changed, 101 insertions(+)
 create mode 100644 README.md
 create mode 100644 index.html
 
$ git remote add origin https://github.com/yves173/bundle1_1.git
 
$ git push -u origin main
 
Username for 'https://github.com': yves173
Password for 'https://yves173@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 908 bytes | 908.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/yves173/bundle1_1.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
 
$ git checkout -b dev 
 
Switched to a new branch 'dev'
 
$ git checkout -b test
 
Switched to a new branch 'test'
 
$ git checkout dev 
 
Switched to branch 'dev'
 
$ git branch -d test
 
Deleted branch test (was f9aead7).
