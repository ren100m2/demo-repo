# Git Commands
A list of beginner friendly Git commands.

## OPTION 1 - Repository pulled/downloaded from GitHub (e.g. to VSCode)

1) git status (check changes)

2) git add . (adds all changes)

3) git commit -m "Msg"

4) git push

## OPTION 2 - Repository created locally

1) cd into the folder and do: git init (creates .git)

2) git add .

3) Create new repo (same name) on GitHub

4) git remote add origin GITHUB_SSH_link_here
    git remote -v (to check)

5) git push -u origin master (to use git push //'upstream')

## GIT BRANCHING

Master Branch

Feature Branch

Hot Fix Branch

1) git branch (check)
2) git checkout -b feature-branch (creates new branch)
3) git checkout master (switch between branches)

---

4) git diff feature-breanch (see the changes)
5) git push --set-upstream origin feature-readme-instr

---

1) Update on GitHub platform
2) git pull master origin (in VS Code terminal)

---

1) git branch (check if you are on master branch)
2) git branch -d feature (removes the branch)
