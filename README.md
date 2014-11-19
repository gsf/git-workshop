# git-workshop

Repo for a Git workshop.


## points to cover

### different workflow configurations
one or few contributors

several contributors

branches w or w/o config files or auth info

pushing to a remote production repository (w or w/o a github repository)
```
git remote -v
```


### merging best practices
on a pull request: `git pull --rebase`

only one commit worth saving: `git cherry-pick`


### how to deal when git hits the fan
nuclear option: `rm -rf`

almost nuclear option: `git reset --hard HEAD`


### rewriting history
recent: `git commit --amend`

archaeology: `git rebase -i HEAD~5`


### commit message etiquette
succinct but specific


## resources
https://jlord.github.io/git-it/

http://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain

https://guides.github.com/introduction/flow/index.html
