# mybash

```
#fi


# Uncomment the following line if you don't like systemctl's auto-paging feature:
# export SYSTEMD_PAGER=

export PATH="~/anaconda3/bin:$PATH"


# User specific aliases and functions


# alias
alias ls="ls -tral"
alias mnt="mount -t smbfs"
alias py="python3"

# ls Directory Colors
LS_COLORS=$LS_COLORS:'di=1;34:'
export LS_COLORS
export CLICOLOR=1

# Functions

# command line header
beginred="\[\e[0;31m\]"
beginblue="\[\e[0;34m\]"
begingreen="\[\e[0;32m\]"

endcolor="\[\e[m\]"
computername="LM-SJN-21012995"

export PS1="✐ $beginred[\A]$endcolor | [\u@$beginblue$computername$endcolor:\w]$beginblue$endcolor$begingreen\n\$ $endcolor"

```
