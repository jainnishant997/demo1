# demo1
demo1@Traversy Media #Git &amp; GitHub Crash Course For Beginners


c264864@VMLRLITCOE-1547 MINGW64 ~
$ git --version
git version 2.22.0.windows.1

c264864@VMLRLITCOE-1547 MINGW64 ~
$ pwd
/h/

c264864@VMLRLITCOE-1547 MINGW64 ~
$ cd git

c264864@VMLRLITCOE-1547 MINGW64 /h/git
$ touch index.html

c264864@VMLRLITCOE-1547 MINGW64 /h/git
$ touch app.js

c264864@VMLRLITCOE-1547 MINGW64 /h/git
$ git init
Initialized empty Git repository in H:/git/.git/

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git config --global user.name 'Nishant Jain'

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git config --global user.email 'nishant.jain3@tcs.com'

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js
        index.html

nothing added to commit but untracked files present (use "git add" to track)

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git add *html

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js


c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git rm --cached index.html
rm 'index.html'

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js
        index.html

nothing added to commit but untracked files present (use "git add" to track)

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git add .

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html


c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   index.html


c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git commit
[master (root-commit) b7795a5]  Initial commit
 2 files changed, 5 insertions(+)
 create mode 100644 app.js
 create mode 100644 index.html

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git add .

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git commit
[master 84de631] Second Commited
 1 file changed, 1 insertion(+), 1 deletion(-)

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git ststus
git: 'ststus' is not a git command. See 'git --help'.

The most similar command is
        status

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git status
On branch master
nothing to commit, working tree clean

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   app.js

no changes added to commit (use "git add" and/or "git commit -a")

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git add .

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git commit -m 'Changed app.js'
[master a1a9304] Changed app.js
 1 file changed, 1 insertion(+)

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ touch .gitignore

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ touch log.txt

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git add .

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   .gitignore


c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git branch login

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git checkout login
Switched to branch 'login'
A       .gitignore

c264864@VMLRLITCOE-1547 MINGW64 /h/git (login)
$ touch login.html

c264864@VMLRLITCOE-1547 MINGW64 /h/git (login)
$ git add .

c264864@VMLRLITCOE-1547 MINGW64 /h/git (login)
$ git status
On branch login
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   .gitignore
        new file:   login.html


c264864@VMLRLITCOE-1547 MINGW64 /h/git (login)
$ git commit -m 'Login'
[login bb1c789] Login
 2 files changed, 6 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 login.html

c264864@VMLRLITCOE-1547 MINGW64 /h/git (login)
$ git checkout master
Switched to branch 'master'

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git merge login
Updating a1a9304..bb1c789
Fast-forward
 .gitignore | 1 +
 login.html | 5 +++++
 2 files changed, 6 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 login.html

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote add demo1 https://github.com/jainnishant997/demo1.git

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote
demo1

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u demo1 master
fatal: unable to access 'https://github.com/jainnishant997/demo1.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ ssh-keygen -t rsa
Generating public/private rsa key pair.
Enter file in which to save the key (/h//.ssh/id_rsa): id_rsa
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in id_rsa.
Your public key has been saved in id_rsa.pub.
The key fingerprint is:
SHA256:+viRhYMc40suHR/JIUPTeWTDPW9ZlloNYS2zkKR+BBM c264864@VMLRLITCOE-1547
The key's randomart image is:
+---[RSA 3072]----+
|      o. +E+..++o|
|     . .o.o==.oo=|
|      = ... .+oB |
|     o B = . .=  |
|      * S o ..   |
|     + = = .     |
|    . = +        |
|     . o .       |
|      ..o        |
+----[SHA256]-----+

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ ssh-keygen -t rsa
Generating public/private rsa key pair.
Enter file in which to save the key (/h//.ssh/id_rsa): id_rsa
id_rsa already exists.
Overwrite (y/n)? n

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ ssh-keygen -t rsa
Generating public/private rsa key pair.
Enter file in which to save the key (/h//.ssh/id_rsa): .ssh
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in .ssh.
Your public key has been saved in .ssh.pub.
The key fingerprint is:
SHA256:0ZOxCcNPxNBQZNQkJAQ9V3sN7DdlHne/YuQL9HU8haQ c264864@VMLRLITCOE-1547
The key's randomart image is:
+---[RSA 3072]----+
|      .=B@X+ooo. |
|        +*=*.oo+*|
|        .=* E..+O|
|         ..o o.+*|
|        S . + ..=|
|           . = . |
|            o o  |
|             .   |
|                 |
+----[SHA256]-----+

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote
demo1

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote add demo1 git@github.com:jainnishant997/demo1.git
fatal: remote demo1 already exists.

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ rm demo1
rm: cannot remove 'demo1': No such file or directory

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote rm demo1

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote add demo1 git@github.com:jainnishant997/demo1.git

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote
demo1

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u demo1 master
The authenticity of host 'github.com (192.30.253.113)' can't be established.
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u demo1 master
Warning: Permanently added the RSA host key for IP address '140.82.114.3' to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote rm demo1

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote add demo1 git@github.com:jainnishant997/demo1.git

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote
demo1

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u demo1 master
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote add demo2 https://github.com/jainnishant997/demo1.git

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u demo2 master
To https://github.com/jainnishant997/demo1.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/jainnishant997/demo1.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote rm demo1

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote rm demo2

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote add origin https://github.com/jainnishant997/demo1.git

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u origin master
To https://github.com/jainnishant997/demo1.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/jainnishant997/demo1.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git rebase origin/master
fatal: invalid upstream 'origin/master'

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote
origin

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push origin master
fatal: unable to access 'https://github.com/jainnishant997/demo1.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u origin master
fatal: unable to access 'https://github.com/jainnishant997/demo1.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote rm origin

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote add origin https://github.com/jainnishant997/demo1.git

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote
origin

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u origin master
fatal: unable to access 'https://github.com/jainnishant997/demo1.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote -v
origin  https://github.com/jainnishant997/demo1.git (fetch)
origin  https://github.com/jainnishant997/demo1.git (push)

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote set-url origin https://github.com/jainnishant997/demo1.git

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git remote -v
origin  https://github.com/jainnishant997/demo1.git (fetch)
origin  https://github.com/jainnishant997/demo1.git (push)

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u origin master
fatal: unable to access 'https://github.com/jainnishant997/demo1.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u origin master
fatal: unable to access 'https://github.com/jainnishant997/demo1.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git config --global --add remote.origin.proxy 40.0.40.10:9000

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push -u origin master
To https://github.com/jainnishant997/demo1.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/jainnishant997/demo1.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git pull --rebase origin master
warning: no common commits
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/jainnishant997/demo1
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> origin/master
First, rewinding head to replay your work on top of it...
Applying:  Initial commit
Applying: Second Commited
Applying: Changed app.js
Applying: Login

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$ git push origin master
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 2 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (13/13), 1.15 KiB | 98.00 KiB/s, done.
Total 13 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/jainnishant997/demo1.git
   1b68256..73dd381  master -> master

c264864@VMLRLITCOE-1547 MINGW64 /h/git (master)
$

