# Week 2 Beginner Boost

* What is a shell and why do I care? 
   * *the shell is the program that interacts with the kernal or operating system. The shell takes the commands given through the command line interface and relays these to the machine (original review answer given (20221203143432))*
* What is the difference between "terminal", "CLI", and "Shell"?
   * *The Terminal is the piece of hardware that one interacts with to access the command line interface*

* What is a REPL?
* What is Unix and Linux? 
* Basic system update and package management and installation
* When to use apt vs apt-get? 
* What is a package? 
* How do I install software? 
* What is an "inode"? Why is everything "just a file"?
* What are UNIX/Linux Permissions?
* What does . and .. mean?
* How do I know that apt packages are safe? 
* what is a shell "history"?

## Commands Used

* man - show manual infomration about a command
* sudo - perform command as root (superuser)
* apt - use interatviely only (ues apt-get in scripts)
* sudo apt update - update all the sources for packages
* sudo apt upgrade - upgrade all packages to latest version
* apt search ^XXX - search for all packages starting with neo
* sudo apt install XXX - install XXX and dependencies
* sudo apt remove XXX - remove XXX
* sudo apt autoremove - automatically remove unused packages
* ls - ist all the files in the current directory
* ls -al - list all the files including hidden (beginning with .)
* hostname - display name of host computer
* pwd - print working idrectory 
* cd foo - change into the foo directory
* cd , cd ~ - change back to the home directory
* cd .. - change into the relative parent directory
* cd ../.. - change into the relative parent of the parent directory
* cd - - change to previous directory (not necessarily the parent directory)
* cd / - change to the root directory

## Related 

* linuxcommand.org
* replit.org
* https://medium.com/@rwxrob/problem-with-repl-it-415f885164f
* "The Unix Operating System"
* Time to rewrite the operating system in rust? - https://www.youtube.com/watch?v=HgtRAbE1nBM
* Intro to Apt - https://www.youtube.com/watch?v=ctGpRWCi8QU




