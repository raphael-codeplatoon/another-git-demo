# CLI Intro

`pwd` - print workign directory

`ls` - list
`ls -a` - list all files, including hidden files

`cd` - change directory

`cd ..` - change to parent directory

`cd ~` - change to home folder

`touch filename.txt` - create a new file

`cp file newfile` - copy a file
`cp -r folder newfolder` - copy a folder

`mv oldfile newfile` - move or rename a file or folder

`rm filename` - delete a file
`rm -r folder` - delete a folder
`rm -rf folder` - delete a folder without confirmation. be careful, there's no undo!

if you get an error when running a command, EACCESS - error, access. Try prefixing that command with "sudo" stands for "super user DO". 
the root user can do anything, but this is dangerous. 

vim is a command-line text editor.

vim has multiple modes: insert mode lets you insert text when you press letters
press <Esc> to get into normal mode
type a colon for ex mode:
    `:wq` - save and quit
    `:q!` - quit without saving


# GIT
git is a commandline program for tracking changes to a project
github.com is a website that hosts git repositories, that enables us to collaborate with each other

`git init` create an empty git repo. creates the `.git`. folder. 
`git status` ask git about the current status of the repo