# SSH

## Start ssh-agent and load your keys
```
$ ps -e | grep [s]sh-agent
9060 ?? 0:00.28 /usr/bin/ssh-agent -l

$ ssh-agent /bin/bash

$ ssh-add ~/.ssh/id_rsa 
$ ssh-add -l
```

## Simplifying connections
```
# contents of $HOME/.ssh/config
Host dev
	HostName dev.example.com
	Port 22000
	User fooey
```
(source: http://nerderati.com/2011/03/17/simplify-your-life-with-an-ssh-config-file/)

