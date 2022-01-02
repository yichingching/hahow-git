# hahow-git
## git commands
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
git branch <sha1> <new branch name> # createa new branch on the branch <sha1>
```
- delete branch
```bash
git branch -D <branch name>
```