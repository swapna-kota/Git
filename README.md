One Time Setup
---
- git config --global user.name "Name"
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
6. To create a commit: `git commit`
7. To push files to remote repostiroty: `git push`
