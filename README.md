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

### How to commit?

- git add (-A, -p, .)
- git commit -m"I am a commit message"
- git push origin master

### Practice

- http://www.wei-wang.com/ExplainGitWithD3/#

## WORKFLOW

### Order Matters

- click 'started' on pivotal tracker story
- type away your code
- git add, git commit, repeat until story is finished
- click 'finished' on pivotal tracker story
- git push, git push heroku master
- click 'deliver' on pivotal tracker story
