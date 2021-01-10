# Git Basic

Learning GitHub

- ### Create or add SSH KEY to GitHub

  - https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

- ### Clone using GitHub Repository using `ssh command`

  - `$git clone git@github.com:jahidmunna/learn_git.git`

- ### File Editing
  1. &nbsp; `i.e: add/edited file: e1.py, e2.py, ...`
  2. &nbsp; `$git add e1.py, e2.py, ...`
  3. &nbsp; `$git commit -m "<your messages>" `
  4. &nbsp; `$git push` &nbsp; <b style='color:red'>(**Caution: Always pull before push**)</b>
- ### Getting Updated Files
  - &nbsp; `$git pull`
- ### To See the Local Changes
  - &nbsp; `$git status`
- ### To See the Git Log Locally
  - &nbsp; `$git log`
- ### To Check all the Branches
  - &nbsp; `$git branch`
- ### To Create or To Go New Branch
  - &nbsp; `$git checkout -b <new_branch>`
- ### To Push New Brach in Remote Repository
  - &nbsp; `$git push --set-upstream origin <new_branch>`
- ### To Switch a Branch
  - &nbsp; `$git checkout <branch_name>`
- ### To Merge from a Branch
  - &nbsp; `$git merge <from_branch_name>`
