# awesome_prompt
This repo contains configuration settings that allows to improve bash prompt


#Nice git prompt
export GIT_PS1_SHOWDIRTYSTATE=1
PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\] \W\[\033[00m\]$(__git_ps1 " \[\e[32m\][%s]\[\e[0m\] ")$ '

