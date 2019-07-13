Github Connection Set Up:
* git init
* git add ./
* git commit
* git remote add origin http://github.com/username/repository-name.git
* git push -u origin master

Caching your Github Password in Git
* git config --global credential.helper osxkeychain

Check update in remote branch:
* git fetch origin && git diff origin/master
* git remote update && git status

Pull data from remote branch
* git pull (git fetch origin && git merge origin/master)
* git pull -r (git pull && git rebase)
