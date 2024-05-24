One Time Setup
---
- git config --global user.name "Full Name"
- git config --global user.email "Email"
- git config --global core.editor "vim"
- ssh-keygen -t ed25519 -C "example@example.com"

Daily Workflow
---
1. To clone a git repostiory: `git clone <URL>`
2. To verify the status of files: `git status`
3. To view modifications to files: `git diff`
4. To add specific file to git: `git add <filename>`
5. To add all files to git: `git add .`
6. To record changes to the files: `git commit`
7. To upload files from local repository to remote repository: `git push`
8. TO download files from remote repository to local repository: `git pull`
9. To list the commits: `git log`
