1) mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hello"
vim one.c
git add
git commit -m "Hi"
git log
git diff

2)mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hello"
vim one.c
git add
git commit -m "Hi"
git branch feature
git checkout feature
git branch feature
git checkout feature
git merge feature
cat one.c

3)mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hello"
git branch feature
git checkout feature
vim one.c
git Stash Save "Changes made"
git branch feature
git checkout feature
cat one.c
git Stash apply
git add .
git commit -m "changes applied from Stash"
git status
cat one.c

4)mkdir spoorthi
cd spoorthi
git init
git clone (create repository paste link)

5)mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hii"
git remote add origin ( paste link)
git push -u origin master

6)mkdir spoorthi
Cd spoorthi
git init 
git status 
vim . C
git add .
git commit -m "custom commit message"

7)mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hello"
vim one.c
git add
git commit -m "Hi"
git v1.0
git tag v1.0
git tag v2.0
git tag
git show v2.0
git push origin v2.0

8)mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hello"
vim one.c
git add
git commit -m "Hi"
git reflog 
git cherry-pick(I'd)

9)mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hello"
vim one.c
git add
git commit -m "Hi"
git show ("1st")
git show ("2nd")

10)mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hello"
vim one.c
git add
git commit -m "Hi"
git show ("1st")
git show ("2nd")
git log --author="   " -- after="   " --before="   "

11)mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hello"
vim one.c
git add
git commit -m "Hi"
git log -n 5

12)mkdir spoorthi
Cd spoorthi
git init 
git status
vim one.c
git add .
git commit -m "Hello"
vim one.c
git add
git commit -m "Hi"
git log
 git reflog
git revert (I'd)
git log --online
