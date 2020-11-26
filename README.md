# Awesome Prompt

## Table of Contents

- [Awesome Prompt](#awesome-prompt)
  - [Table of Contents](#table-of-contents)
  - [About <a name = "about"></a>](#about-)
  - [Git Branch <a name = "git_branch"></a>](#git-branch-)


## About <a name = "about"></a>

This repo stores useful scripts that allows to power up your bash prompt

## Git Branch <a name = "git_branch"></a>

This code allows to see the git branch if there is git in the folder

```bash
#Nice git prompt
export GIT_PS1_SHOWDIRTYSTATE=1
PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\] \W\[\033[00m\]$(__git_ps1 " \[\e[32m\][%s]\[\e[0m\] ")$ '
```
