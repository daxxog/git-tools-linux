git-tools-linux
==========

Shell scripts to easily add, commit, and push all in one command.

Install (to a local repo): 
-------------
```bash
wget https://github.com/daxxog/git-tools-linux/tarball/master -O git-tools-linux.tar.gz
curl -sS https://raw.github.com/daxxog/git-tools-linux/master/.gitignore >> .gitignore
tar xvfz git-tools-linux.tar.gz
rm git-tools-linux.tar.gz
mv *git-tools-linux* devtools
cd devtools
nano gitpush.sh
```

Usage:
-------------
```bash
cd devtools
./gacp.sh
```

*Note: you must edit gitpush.sh before using.*