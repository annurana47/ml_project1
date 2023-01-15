Start Machine Learning Project:
===============================

Requirements:

1. [Github Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com)
4. [Git CLI](https://git-scm.com)


creating conda environment

```
conda create -p venv python==3.7 -y
```
To activate the venv

```
conda activate venv 

OR

conda activate venv/
```

To install requirements.txt 

```
pip install -r requirements.txt
```
To add file to git

```
git add .

OR

git add <file_name>
```
Note: To ignore file and folder from git add command, we can write name of file or folder in .gitignore file

To check the git status
```
git status
```
To check all the versions maintained by git
```
git log
```
To create version/commit all changes by git
```
git commit -m "message"
```
To send version/changes to github
```
git push origin main
```
To check remote url
```
git remote -v
```
To check git branch
```
git branch
```