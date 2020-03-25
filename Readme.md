:: Github Course ::  
https://www.udemy.com/course/git-e-github-para-iniciantes


### config user name  
git config --global user.name "paulofrancis"

### config global email  
git config --global user.email "paulofrancis88@gmail.com"

### config editor   
git config --global core.editor notepad++

### list all config  
git config --list 

### init  
git init 

### check status  
git status

### add file to staged status  
git add "file name"

### commit  
git commit -a (add) -m (message) "message"

### log  
git log --decorate --author="paulofrancis"  
git shortlog -sn  
git log --graph  
git show "commit hash"  

### show diff  
git diff  
git diff --name-only

### reseting changes  
git checkout "file name"

### removing file from staged  
git reset HEAD "file name"

### reset commit  
git reset --soft "commit hash" -> undo files to staged  
git reset --mixed "commit hash" -> undo files to modified  
git reset --hard "commit hash" -> undo all files 

### add remote repository  
git remote add origin git@github.com:paulofrancis/github-course.git  
git remote -> check remote repository  
git remote -v -> show more info  

### push to remote  
git push -u origin master -> first push  
git push origin master -> to from  

### clone  
git clone git@github.com:paulofrancis/github-course.git "folder name opt"

### branch  
git checkout -b test  
git branch  
git checkout "branch name" -> switch between branches  
git branch -D "branch name" -> delete branch  

### merge  
git merge "branch from name"  

### stash  
git stash  
git stash apply  
git stash list  
git stash clear  

### alias  
git config --global alias.s status  
git s -> status  

### tags  
git tag -a 1.0.0 -m "message"  
git push origin master --tags  
git tag -d "tag" -> delete  
git tag  

### revert  
git revert "commit hash"  

### delete remote repository  
git push origin :tag or :branch  
