:: Github Course ::  
https://www.udemy.com/course/git-e-github-para-iniciantes


-- config user name  
git config --global user.name "paulofrancis"

-- config global email  
git config --global user.email "paulofrancis88@gmail.com"

-- config editor   
git config --global core.editor notepad++

-- list all config  
git config --list 

-- init  
git init 

-- check status  
git status

-- add file to staged status  
git add "file name"

-- commit  
git commit -a (add) -m (message) "message"

-- log  
git log --decorate --author="paulofrancis"  
git shortlog -sn  
git log --graph  
git show "commit hash"  

-- show diff  
git diff  
git diff --name-only

-- reseting changes  
git checkout "file name"

-- removing file from staged  
git reset HEAD "file name"

-- reset commit  
git reset --soft "commit hash" -> undo files to staged  
git reset --mixed "commit hash" -> undo files to modified  
git reset --hard "commit hash" -> undo all files 

-- add remote repository  
git remote add origin git@github.com:paulofrancis/github-course.git  
git remote -> check remote repository  
git remote -v -> show more info  

-- push to remote  
git push -u origin master -> first push  
git push origin master -> to from  

