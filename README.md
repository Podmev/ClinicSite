# ClinicSite
Site for dental clinic

[Dashboard](https://trello.com/b/8GDwPlRE/clinic-site)

Git flow
1. Main branch is master, it should be stable
2. Developping should be in separate branches for small features
3. After finishing feature, branch should me merged to master branch
4. For next feature should be used ne branch, created from actual master
5. It is easier if separate developpers work on different features in different branches

How to use git in main branch:
1. git pull, before changes - it needed to get all updates
2. git add . , to add all
3. git commit -m "<commit message>"
4. git push

How to develop in own branch:
1. git checkout -b "<branch-name>"
2. usual commits and push to branch
3. git push –set-upstream origin <branchName>, on first push
4. when feature of branch is finished it should be merged to main branch

How to merge branch to master
1. git checkout branch
2. git merge master
3. maybe fix merge conflicts and commit and push them  (in branch)
4. git checkout master
5. git merge branch