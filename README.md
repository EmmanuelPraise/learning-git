*** LEARNING HOW TO USE GIT & GITHUB

$ git --version  <- This is to check if git is install on your PC
$ git config --global color.ui auto
$ git config --global user.name "yourusername"
$ git config --global user.email "example@gmail.com"

Note: Use global to set the username and e-mail for every repository on your computer.
If you want to set the username/e-mail for just the current repo, you can remove global

$ mkdir example  <- this creates a directory named example on your PC
$ cd example  <- This changes the directory you are currently in to example
$ git init  <-- This is to initialize git into the example folder and creates a new repository in your PC
$ rm -rf .git  <-- To delete/uninitialize a git repository
$ touch index.html
$ touch script.js
$ touch style.css
The above command "touch" is used to name the files index.html, script.js, style.css in the example folder
$ ls  <-- This is to list the files in the example folder
index.html  script.js  style.css
$ git add index.html  <-- add/stage index.html to the repo
$ git rm --cached index.html  <-- this is to unstage index.html from the repo
rm 'index.html'
$ git add .  <-- add/stage all in the directory
$ git add -A  <-- same as above
$ git add --all  <-- same as above
$ git status
$ git rm -r --cached .  <-- to unstage/remove all in the directory
$ git commit -m "My commit Message"
$ git log  <-- To view the history of commits for a repository
$ git branch -M branch_name  <-- This is to create a branch
$ git branch -d branch_name  <-- This is to delete a branch
$ git branch  <-- This is to check all the branches in that repository
* master  <-- '*' Shows that you are currently on this branch
main
$ git checkout branch_name  <-- This is to switch from one branch to another
$ git remote add origin https://github.com/yourusername/example.git
$ git push -u origin main


other
git --help
ctrl + l
git show
cd .. --> to go back
dir
git config
git config -l
ls -a
git merge main
