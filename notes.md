command
git -v
git config --global user.name "Ahmad Abuzar"
git config --global user.email "ahmadabuzar0786@gmail.com"
 
to check config at global level

git config --global --list

making vs code default editor  
git config --global core.editor "code --wait";

cross platform compatibility -->
git config --global core.autocrlf true

initialiaze git into folder 
git init 
git add f1.txt   move to staging area
git add f1.txt f2.txt index.html  move to staging area(space de de kr file name)
git rm --cached f1.txt      move from staging to working area for the first file onlyyyyyy

git commit -m "First Commit"   to commit all files must be in staging area


git commit --amend -m "New Commit Message"
git commit --amend --no-edit
uhnhnjh

