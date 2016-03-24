# SubEdit

An interface for browsing files on a remote linux machine and opening them in Sublime Text over a secure ssh tunnel. Also supports searching and creating new files in Sublime.

First, make sure you've installed the [rsub](https://github.com/henrikpersson/rsub) Sublime package and updated your local ssh config file according to the rsub instructions.

Then install subedit on the remote machine:
```
sudo wget -O /usr/local/bin/subedit https://raw.githubusercontent.com/mgrahamjo/subedit/master/subedit && sudo chmod +x /usr/local/bin/subedit
```

Now you can start browsing files from anywhere with the command `subedit`.

If you don't have rsub and dialog installed on the remote machine, they will be installed the first time you run `subedit`. 
