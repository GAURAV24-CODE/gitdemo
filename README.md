git --version

git config --global user.name "Gaurav Kumbhar"
git config --global user.email "kumbhargaurav24@gmail.com"

mkdir my-project
cd my-project
git init
git status

echo Hello Git > index.html
git status

git add index.html
git status

git commit -m "Add new project files"

git log
git log --oneline
git status

git branch
git checkout -b feature1
git branch

notepad index.html
git status

git add index.html
git status

git commit -m "Added new line in index.html"
git log --oneline

git checkout master
git branch

git diff master feature1

git merge feature1

git log --oneline

git branch -d feature1

git branch
git status
