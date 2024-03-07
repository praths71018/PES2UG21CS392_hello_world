## How to push a repository in Github 
1. prathamshetty@Prathams-MacBook-Air Github Actions A4 % git init <br>
hint: Using 'master' as the name for the initial branch. This default branch name  <br>
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
2. prathamshetty@Prathams-MacBook-Air Github Actions A4 % git checkout -b main <br>
Switched to a new branch 'main' <br> <br>
3. prathamshetty@Prathams-MacBook-Air Github Actions A4 % git remote add origin https://github.com/praths71018/PES2UG21CS392_hello_world.git <br> <br>
4. prathamshetty@Prathams-MacBook-Air Github Actions A4 % git add . <br> <br>
5. prathamshetty@Prathams-MacBook-Air Github Actions A4 % git commit -m "Describe this commit" <br>

[main (root-commit) 06e2001] Describe this commit <br>
 2 files changed, 11 insertions(+) <br>
 create mode 100644 CMakeLists.txt <br>
 create mode 100644 main.cpp <br> <br>
6. prathamshetty@Prathams-MacBook-Air Github Actions A4 % git log <br>
commit 06e200114717d598cb6a14e0f499cb642771b3c0 (HEAD -> main) <br>
Author: Pratham <prathamshetty0825@gmail.com> <br>
Date:   Fri Mar 8 05:22:55 2024 +0530 <br>

    Describe this commit 
 <br> <br>
7. prathamshetty@Prathams-MacBook-Air Github Actions A4 % git push -f origin main <br>
Enumerating objects: 4, done. <br>
Counting objects: 100% (4/4), done. <br>
Delta compression using up to 8 threads <br>
Compressing objects: 100% (4/4), done. <br>
Writing objects: 100% (4/4), 464 bytes | 464.00 KiB/s, done. <br>
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/praths71018/PES2UG21CS392_hello_world.git
 * [new branch]      main -> main <br> <br>
prathamshetty@Prathams-MacBook-Air Github Actions A4 %
<br>
