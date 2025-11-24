# git commands
## create local repo
`git init` - create git
`git remote -v` - show remote repo link\
`git remote add origin git@github.com:alinakrivecc/docs.git` - add repo link\
`git push -u origin master` - send to remote git\

## config 
`git config --global user.name` - add name in projects\
`git config --global user.email` - add email 

## clone

`git clone https://github.com/user/project.git` - clone remote repo
`git checkout -b develop` - create new branch
`git checkout master` - go to branch master
`git pull` - get repo updates if somebody did it

## commit
`git status` - show uncommited(unstaged) \
`git diff` - show file changes\
`git add folder_name` - add chosen files to be commited (staged)\
`git add .` - add all \
`git commit -am 'docs: add unix doc` - commit all\
`git commit -m 'docs: add unix doc'` - commit\
`git commit --amend -m "docs: add git clone commands"` - rewrite last commit if needed
`git push` - send to remote repos