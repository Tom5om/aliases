aliases
=======

Git aliases

Copy the bashrc file to your home directory and rename it to .bashrc

This bashrc will make sure you see which branch you are in and gives you some handy aliasses.

Aliasses you can use are:

alias gpl = "git pull origin master" # pull latest from master
alias gps="git push origin master" # push to master
alias gcm="git checkout master" # checkout master
alias gs="git status" # git status
alias gt="git fetch --tags ; git tag | sort -V" #fetch new tags and show current tags
alias gta=tagForDeployment # tag for deployment use param
alias gc=commitWithComment # Git commit with comment
alias gpt="git push origin --tags" # push the tags to origin
alias gtp="git push origin --tags" # push the tags to origin
alias gcma=commitAddWithComment # Git commit with comment
alias cmpu="composer update -vvv" #composer update
alias gtap=createNewTag #get tags, increment a new tag
