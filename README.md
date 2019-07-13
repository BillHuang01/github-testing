Github Connection Set Up:
* git init
* git add ./
* git commit
* git remote add origin http://github.com/username/repository-name.git
* git push -u origin master

Caching your Github Password in Git
* git config --global credential.helper osxkeychain

Pull data from remote branch
* git pull (git fetch origin & git merge origin/master)
* git pull -r (git pull & git rebase) -- moves commit of one branch on top of the other instead of creating new commit for the merge
