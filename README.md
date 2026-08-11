# GIT

1.**pwd**---gives the path of the project you are working on(current folder).
2.**ls**---list of files and folders your working directory contains.
3. **cd<project folder name>**---move into your wished directory.
GIT INITIALIZING
1.**git status**--- check whether the folder is a git repository if it is no need of git init.
2.**igit init**---if git status is fatal initialize the git.
3.**git remote -v**----shows which github repository your local project connected to.
4.**git branch --show-current**---shows your current branch main or master
5.check your .gitignore it tells git don't put these files/folders in github backup.
ADDING PROJECTS TO GIT
1.**git add .**---prepare all the files execpt .gitignore for backup to github.it doesnt upload anything to github just preparing
2.**git status**---shows the files that git is preparing to commit.
COMMIT
1.**git commit -m "comments"**-----it creates a snapshot of your prjoect in GIT
PUSH
1.**git push -u origin main**----this is the command that actually sends your files to github.
AUTHENTICATION IF ASKED

if authentication which is previously a your username amd password of github but now it is personal access tokens for HTTP pushes.
for token access go to your github profile settings then developer settings and then tokens choose classic tokens give it a description you can chose token expiration and scope as repo and create copy that token very important.
 next if password amd  username is not asked and your getting authentication fail error do this **git config --global --unset credential.helper** then **git remote set-url origin https://Lehari891:your token@git
hub.com/Lehari891/Fiori-launchpad.git** this removes authentication error.then do **git push -u origin main** dont add readme first while creating the repository.

then check git status.for successful uploading.


