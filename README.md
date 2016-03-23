# subtree

An interface for browsing files on a remote linux machine and opening them in Sublime Text over a secure ssh tunnel.

First, make sure you've installed the [rsub](https://github.com/henrikpersson/rsub) Sublime package.

Then install the subtree script to your $PATH on the remote machine:
```
sudo wget -O /usr/local/bin/subtree https://raw.githubusercontent.com/mgrahamjo/subtree/master/subtree
```

Now you can start browsing files from anywhere with the command `subtree`.

The first time you run it it will install up to two dependencies using yum and wget.