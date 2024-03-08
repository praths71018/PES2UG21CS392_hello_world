## How to push a repository for 1st time in Github 
1. prathamshetty@Prathams-MacBook-Air Github Actions A4 % ```git init``` <br><br>
>hint: Using 'master' as the name for the initial branch. This default branch name  <br>
hint: is subject to change. To configure the initial branch name to use in all <br>
hint: of your new repositories, which will suppress this warning, call: <br>
hint:  <br>
hint:   git config --global init.defaultBranch <name> <br>
hint:  <br>
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and <br>
hint: 'development'. The just-created branch can be renamed via this command: <br>
hint:  <br>
hint:   git branch -m <name> <br>
Initialized empty Git repository in /Users/prathamshetty/Desktop/Sem 6/Cloud Computing/Lab/Assignment 4/Github Actions A4/.git/ <br> <br>
2. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git checkout -b main ``` <br><br>
>Switched to a new branch 'main' <br> <br>
3. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git remote add origin https://github.com/praths71018/PES2UG21CS392_hello_world.git  ```<br> <br>
4. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git add . ``` <br> <br>
5. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git commit -m "Describe this commit"  ```<br><br>
>[main (root-commit) 06e2001] Describe this commit <br>
 2 files changed, 11 insertions(+) <br>
 create mode 100644 CMakeLists.txt <br>
 create mode 100644 main.cpp <br> <br>
6. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git log```<br><br>
>commit 06e200114717d598cb6a14e0f499cb642771b3c0 (HEAD -> main) <br>
Author: Pratham <prathamshetty0825@gmail.com> <br>
Date:   Fri Mar 8 05:22:55 2024 +0530 <br>
    Describe this commit 
 <br> <br>
7. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git push -f origin main ``` <br><br>
>Enumerating objects: 4, done. <br>
Counting objects: 100% (4/4), done. <br>
Delta compression using up to 8 threads <br>
Compressing objects: 100% (4/4), done. <br>
Writing objects: 100% (4/4), 464 bytes | 464.00 KiB/s, done. <br>
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0<br>
To https://github.com/praths71018/PES2UG21CS392_hello_world.git<br>
 <blink>*</blink> [new branch]      main -> main <br> <br>
prathamshetty@Prathams-MacBook-Air Github Actions A4 %
<br><br>

## How to push changes in local system to github
1. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git add .``` <br> <br>
2. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git commit -m "Modified commit"  ```<br><br>
3. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git push -f origin main ``` <br><br>

## How to pull changes in Github to local system
1. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git fetch origin```<br><br>

>remote: Enumerating objects: 13, done.<br>
remote: Counting objects: 100% (13/13), done.<br>
remote: Compressing objects: 100% (9/9), done.<br>
remote: Total 11 (delta 2), reused 0 (delta 0), pack-reused 0<br>
Unpacking objects: 100% (11/11), 4.01 KiB | 456.00 KiB/s, done.<br>
From https://github.com/praths71018/PES2UG21CS392_hello_world<br>
   06e2001..c36a568  main       -> origin/main<br>
<br><br>

2. prathamshetty@Prathams-MacBook-Air Github Actions A4 %  ```git merge origin/main```<br><br>

>Updating 06e2001..c36a568<br>
Fast-forward<br>
 .github/workflows/main.yml | 20 ++++++++++++++++++++<br>
 README.md                  | 41 +++++++++++++++++++++++++++++++++++++++++<br>
 main.cpp                   |  2 +-<br>
 3 files changed, 62 insertions(+), 1 deletion(-)<br>
 create mode 100644 .github/workflows/main.yml<br>
 create mode 100644 README.md<br>
