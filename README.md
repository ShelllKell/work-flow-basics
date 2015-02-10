# Work Flow Basics

## GIT

### Creating A New Rails App

- make repo on github
- copy first clipboard and paste it into terminal
- work away!

### Cloning From an Exsisting Repo

- copy the SSH clone URL from desired repo
- make a new directory on your machine, cd into that directory, and type 'git clone #{SSH clone URL}'
- git remote rm origin
- copy second clipboard from your repository's page, paste into terminal
- work away!

- *Use git remote -v*  << this will show you what remotes you have set up

### How to commit?

- git add (-A, -p, ., file_name, --help)
- git commit -m"I am a commit message"
- repeat until a feature is done
- git push origin master

- Writing good commit messages: https://github.com/erlang/otp/wiki/Writing-good-commit-messages

### Shelby, do I have to push to Github to push to Heroku?!

 - No! But I would, to keep your versions in sync.

### Practice

- main branch is always called master
- the branch we are currently on is called HEAD
- http://www.wei-wang.com/ExplainGitWithD3/#

## WORKFLOW

### Order Matters

- click 'started' on pivotal tracker story
- type away your code
- git add, git commit, repeat until story is finished
- click 'finished' on pivotal tracker story
- git push, git push heroku master
- click 'deliver' on pivotal tracker story
