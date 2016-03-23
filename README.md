# SubTree

An interface for browsing files on a remote linux machine and opening them in Sublime Text over a secure ssh tunnel.

First, make sure you've installed the [rsub](https://github.com/henrikpersson/rsub) Sublime package and updated your ssh config file according to the instructions.

Then install SubTree on the remote machine:
```
sudo wget -O /usr/local/bin/subtree https://raw.githubusercontent.com/mgrahamjo/subtree/master/subtree
```

Now you can start browsing files from anywhere with the command `subtree`.

If you don't have rsub and dialog installed on the remote machine, they will be installed the first time you run `subtree`. 
