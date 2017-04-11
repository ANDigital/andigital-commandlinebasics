# Command line basics
This repository is the playground for a Command Line Basics course.

## Command reference
`ls` - list files

`cd <directory>` - change to another working directory

`pwd` - print the current working directory

`mv <source> <destination>` - move files or directories

`cp <source> <destination>` - create a copy of a file

`rm <file>` - remove a file


## Tasks
1. Clone this repository: `git clone https://github.com/andigital/andigital-commandlinebasics.git`
1. We accidentally placed `archive_help.txt` in the code directory, when it should be in archives. Move it to the right place.
1. In the code directory, create a backup of `main.js` with the name `main.js-backup20170322`
1. There is an unneeded file in the tmp directory. Remove it.
1. In the code directory, there is a typo in the filename of `tsets.js`. It should be called `tests.js`. Rename it.
1. Change the Dockerfiles in the archives directory to use Node 8 (change `FROM node:7-onbuild` to `FROM node:8-onbuild` inside the files).

## Bonus task
Write a shell script to automate the above tasks.
