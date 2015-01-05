#dp

dp is an extensible tool for creating and installing automated scripts onto
your system.

dp is based upon a rough, hacked-together bash script as well as makefiles.

###usage

dp structures its commands as `dp package task arg1=val1...argn=valn`

###installing packages

dp packages can be installed by using `dp install username/repo` where username is the Github username of the author, and repo is the repo name of the package.

###uninstalling packages

dp packages can be uninstalled by using `dp uninstall package_name` where package_name is the name of the package. You do not need to supply the author name in this case.

###developing packages

dp is designed so that package developers can build simple makefile scripts and host them on github so that users may add and remove packages as they see fit.

All a developer needs to do is create a repo with a makefile containing appropriate targets.
