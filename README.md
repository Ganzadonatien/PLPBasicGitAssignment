# PLPBasicGitAssignment



Nziza Donatien@DESKTOP-0NHD2BL MINGW64 ~
$ cd desktop/PLPBasicGitAssignment

Nziza Donatien@DESKTOP-0NHD2BL MINGW64 ~/desktop/PLPBasicGitAssignment
$ git init
Initialized empty Git repository in C:/Users/Nziza Donatien/Desktop/PLPBasicGitAssignment/.git/

Nziza Donatien@DESKTOP-0NHD2BL MINGW64 ~/desktop/PLPBasicGitAssignment (master)
$ git remote add origin  https://github.com/Ganzadonatien/PLPBasicGitAssignment.git

Nziza Donatien@DESKTOP-0NHD2BL MINGW64 ~/desktop/PLPBasicGitAssignment (master)
$ echo Hello, Git! > hello.txt


Nziza Donatien@DESKTOP-0NHD2BL MINGW64 ~/desktop/PLPBasicGitAssignment (master)
$ git add hello.txt
warning: in the working copy of 'hello.txt', LF will be replaced by CRLF the next time Git touches it

Nziza Donatien@DESKTOP-0NHD2BL MINGW64 ~/desktop/PLPBasicGitAssignment (master)
$ git commit -m "Add hello.txt with a greeting"
[master (root-commit) 6003dfc] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

Nziza Donatien@DESKTOP-0NHD2BL MINGW64 ~/desktop/PLPBasicGitAssignment (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 238 bytes | 238.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Ganzadonatien/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/Ganzadonatien/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
