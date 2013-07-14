git-shell-commands
==================

Commands of git-shell for simple

## Setup

### Create user

    useradd git

### Add authorizetion_keys

    # mkdir /home/git/.ssh
    # vi /home/git/.ssh/authorizetion_keys
    # cd /home/git/
    # chown git .ssh .ssh/authorizetion_keys
    # chgrp git .ssh .ssh/authorizetion_keys
    # chmod 700 .ssh
    # chmod 600 .ssh/autoraizetion_keys
    
### Change login shell

    # /etc/passwd
    git:x:1001:1001::/home/git:/usr/local/bin/git-shell

### Clone this git-shell-commands and make dir

    # cd /home/git
    # git clone git@github.com:pesblog/git-shell-commands.git
    # mkdir git git.bak
    # chown git git git.bak git-shell-commands
    # chgrp git git git.bak git-shell-commands
    # chmod 700 git git.bak git-shell-commands

### Let's login

    $ ssh git@your-host-name.com
    usage:
     ls
     init <name>
     rm   <name>
     help
    >_