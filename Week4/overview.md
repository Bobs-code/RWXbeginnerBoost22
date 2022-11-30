# Week 4 Overview

* How to reconnect to a saved VM session with SSH (20221125102432)
* What is a home directory? - Place for a user to place their file which has particular permissions and privileges which are seperate from the root's/admin permissions. Computers traditionally had multiple users and allows us to separate permissions and keep other parts of the system safe. 
* How to update computer?? apt-update grabs the copies of the libraries that we are getting ready to install (20221130192704)
* What are permissions and why do I care? (20221130194206)
* everything is an inode ("file") (20221130195151)

BREAK 20221130200344

* Change the permissions on a file (20221130201403)
* Danges of `setuid`? (20221130211411)

BREAK 20221130211411

* How do i change user or group of file or directory? 20221130211617


## Commands

* apt lst --upgradable
* `mv foo other` = change file/directory foo name to other (or move)
* `cp foo other` = copy file/directory foo to other
* ls - List the file in the current directory
* `stat foo` - see all the file details about the foo  inode
* `stat -c '%a'` - to see octal persmissions 
* `chown rando foo` - change ownership of foo to rando
* `chmod` - change the permissions on a file
* `ls -ld .` - view permissions in the current directory
* `ls -ld <file/directory name>` - view permissions of file/directory
* `sudo adduser foo` - add new user
* `sudo deluser foo` - remove user
* `echo foo` - write foo to standard output
* `cat foo` - write content of foo to standard output
* `which foo` - print the full file path to the executable file
* `ls -l $(which sudo)` - list perms for sudo command
* `sudo pssword foo` - change password for foo user
* `ip -c  a` - lookup IP addresses
* `touch` - create new text file or update time stamp
* `grep` - search for a key word in a file (global regular expression print)



# Quick notes

* host/client name = name of the server you are on

## Related 

* Read about Unix Timeshare
* Watch Triumph of the nerds
* picoCTF


