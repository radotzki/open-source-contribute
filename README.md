## Init a project
1. Fork the codebase
2. git clone the forked version
3. git remote add upstream <original-codebase>
4. git fetch upstream
5. git branch --set-upstream-to=upstream/master master
6. git checkout -b pr/<feature-name>
7. git push -u origin pr/<feature-name>

## Send a PR
1. git add .
2. git commit -m ""
3. git push
4. from github: create pull request button

## Update a PR
1. git fetch upstream
2. git rebase upstream master
3. git commit
4. git push -f