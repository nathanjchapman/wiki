# Start ssh-agent and load your keys
```
$ ps -e | grep [s]sh-agent
9060 ?? 0:00.28 /usr/bin/ssh-agent -l

$ ssh-agent /bin/bash

$ ssh-add ~/.ssh/id_rsa 
$ ssh-add -l
```
