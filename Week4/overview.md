# Week 4 Overview

* How to reconnect to a saved VM session with SSH (20221125102432)
* What is a home directory? - Place for a user to place their file which has particular permissions and privileges which are seperate from the root's/admin permissions. Computers traditionally had multiple users and allows us to separate permissions and keep other parts of the system safe. 
* How to update computer?? apt-update grabs the copies of the libraries that we are getting ready to install (20221130192704)
* What are permissions and why do I care? (20221130194206)
* everything is an inode ("file") (20221130195151)

## Commands

* apt lst --upgradable
* ls - List the file in the current directory
* `stat foo` - see all the file details about the foo  inode
* `stat -c '%a'` - to see octal persmissions 
* `chmod` - change the permissions on the file
* `ls -ld .` - view permissions in the current directory
* `ls -ld <file/directory name>` - view permissions of file/directory



# Quick notes

* host/client name = name of the server you are on

## Related 

* Read about Unix Timeshare
* Watch Triumph of the nerds
* picoCTF


