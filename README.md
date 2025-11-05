# Demo13_1_SD_Raw

# create a new repository on the command line
echo "# Demo13_1_SD_Raw" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/wenchm/Demo13_1_SD_Raw.git
git remote -v
git push -u origin master

# push an existing repository from the command line
git remote add origin https://github.com/wenchm/Demo13_1_SD_Raw.git
git branch -M master
git push -u origin master

# add all files and dir
git status
git add .
git commit -m "origin"
git push -u origin master