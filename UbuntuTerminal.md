# Using Terminal in Ubuntu
## Basics
Open Terminal: Ctrl+Alt+T, or find it in Applications  
Most commands: command [options] [args]  
Options usually  preceded by - or --, eg -h or --help  
Up arrow key: previous command

## File System
/ is used to separate directories, and / is the root directory of the filesystem   
~ represents your home directory, or the directory for your user  
. represents the current directory  
.. represents the parent directory  
. is also used to precede hidden files or directories

ls: list contents of a directory (folder)  
cd: change directory  
mkdir: create a directory  
rm: remove (delete) a file. rm -r to remove a folder.  
Tab key: auto-complete path

## Getting Help
Most commands have a -h or --help option  
man [command] will open the manual page  
man -k [keyword] will search manual pages for a term

## Package Management
sudo apt update  
sudo apt upgrade  
sudo apt install [package]  
sudo apt remove [package]  
apt-cache search [keyword] 

## For futher exploration...
find, grep  
top, kill  
touch, echo, awk, less, cat, sed, |  
