git-shell-commands
==================

Commands of git-shell for simple

## Setup

### Create user

    # useradd git

### Add authorized_keys

    # mkdir /home/git/.ssh
    # vi /home/git/.ssh/authorized_keys
    # chown -R git:git /home/git/.ssh
    # chmod 700 /home/git/.ssh
    # chmod 600 /home/git/.ssh/autoraizetion_keys
    
### Change login shell to git-shell

`git-shell` place is `which git-shell`

    # /etc/passwd
    git:x:1001:1001::/home/git:/usr/local/bin/git-shell

### Clone this git-shell-commands and make dir

    # cd /home/git
    # git clone git@github.com:pesblog/git-shell-commands.git
    # mkdir git git.bak
    # chown -R git:git git git.bak git-shell-commands
    # chmod 700 git git.bak git-shell-commands

### Let's login

    $ ssh git@your-host-name.com
    usage:
     ls
     init <name>
     rm   <name>
     help
    >_
