# hahow-git
## git commands
### Initial settings
- setting configuration
```bash
git config --global user.name "your user name"
git config --global user.email "your email address@gmail.com"
```
- initial
```bash
git init
```
### Basic
- from HEAD to local repository
```bash
git add .
git commit -m "message"
```
- upload to remote repository
```bash
git push origin <branch name>
```
### Branch
- create branch
```bash
git branch <new branch name> # create a new branch on the branch our HEAD is on
git branch <sha1> <new branch name> # create new branch on the <sha1> commit (branch)
```
- delete branch
```bash
git branch -D <branch name>
```
- switch branch
```bash
git checkout <branch name>
```
### Information
- show historical commit
```bash
git log
```
- show historical commit and branch on GUI
```bash
gitk
```