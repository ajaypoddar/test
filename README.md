# Example Repository
This is a sample repo, hello my dear world!

now making the second change

# basic commands

# clone / download
git clone URL Directory

# check the status of the files in the folder
git status

# info of the git commit, local vs master
git log

# add the file to be committed later
git add FILE_NAME

# commit the changes to the branch
git commit -m "commit name"

# push the changes to online git account
git push origin master

# see the difference in the files
git diff FILE_NAME

# undo the changes and restore to old version of the file
git checkout FILE_NAME

# undo and redo git
git log
git checkout COMMIT_ID
git status
git log
git checkout master
git status
git log

# I've been using this really cool git command for a long time called git lg. It's like git log but wayyyyyyyy better.
git log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %><(55,trunc)%s%C(red)%d%C(reset) %C(blue)[%an]%C(reset) %C(yellow)%ad%C(reset)%n'

# git course by kalob.io
https://www.udemy.com/share/101wMUA0oadl5bQXg=/

