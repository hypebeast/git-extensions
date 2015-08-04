# git-extensions

My personal git things.

Installation
============

In order to use the git-extensions scripts as new subcommands with git, 
they need to be available in your PATH.

Option 1
--------

Add the `git-extensions` directory to your `PATH`:

    export PATH=$PATH:~/git-extensions/bin

The additional git commands can be used like any other git command.

E.g. to show tickets that are part of a revision

    git tickets


Option 2
--------

Use the Makefile to copy the scripts to your `/usr/local/bin` directory.

    make install

To remove the scripts and man pages run `uninstall`:

    make uninstall

Commands
=========

* `git tickets` -> Generate a list with all tickets which are included in a specific revision, but not in another revision
