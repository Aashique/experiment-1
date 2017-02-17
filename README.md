QUE1:Getting started with Linux basic commands and directory structure, execute file, directory
operations.
Aim
***
Getting started with Linux basic commands and directory structure, execute file,
directory operations.
Creating Files And Directories
*******************************
touch <filename> ---- create a new file
mkdir <dirname> ---- create a new directory
Current/working Directory
**************************
1) Current Directory can be found out by pwd.
pwd stands for “print working directory”
2) Change Directory
command cd is used to change directory
cd <dirname>
Special Directories
*******************
1 )Current Directory ====> .
2 ) Parent directory of
the current directory ====> ..
3 )Home Directory ====> ~
4 )Root Directory ====> /
5 )Another user’s directory ====> ~<username>
Viewing Contents Of A Text Files
********************************
1 )cat <filename> display the text scroll off the screen
2 )cat <file1> <file2> concatenate two files
3 )more <filename> display the file one scornful at a time
4 )less <filename> similar but faster than more
Listing Files And Directories
*****************************
1 )ls ---- list files in the current directory
2 )ls -l ---- provide a long listing of all files
3 )ls -l -h ---- same as above command but size will
be in human readable forms
4 )ls -F ---- marks all executables with * and
directories with /
5 )ls —color ---- shows a coloured listing of files
6 )ls -a ---- shows all files in the present directory
including special dot files
Copying Files And Directories
*****************************
1 )cp <file1> <file2> ====> copy file1 to file2
2 )cp <file1> <dirname> ====> copy file1 to directory dirname
3 )cp -r <dirname1> <dirname2> ====> copy dirname1 directory to dirname2
directory recursively
Renaming And Moving Files
*************************
1 )mv <oldname> <newname> ---- renames file with old name to new
name
2 )mv <olddir> <newdir> ---- renames directory with olddir to
newdir
3 )mv <filename> <dirname> ---- moves file to the directory
QUE1:Getting started with Linux basic commands and directory structure, execute file, directory
operations.
Aim
***
Getting started with Linux basic commands and directory structure, execute file,
directory operations.
Creating Files And Directories
*******************************
touch <filename> ---- create a new file
mkdir <dirname> ---- create a new directory
Current/working Directory
**************************
1) Current Directory can be found out by pwd.
pwd stands for “print working directory”
2) Change Directory
command cd is used to change directory
cd <dirname>
Special Directories
*******************
1 )Current Directory ====> .
2 ) Parent directory of
the current directory ====> ..
3 )Home Directory ====> ~
4 )Root Directory ====> /
5 )Another user’s directory ====> ~<username>
Viewing Contents Of A Text Files
********************************
1 )cat <filename> display the text scroll off the screen
2 )cat <file1> <file2> concatenate two files
3 )more <filename> display the file one scornful at a time
4 )less <filename> similar but faster than more
Listing Files And Directories
*****************************
1 )ls ---- list files in the current directory
2 )ls -l ---- provide a long listing of all files
3 )ls -l -h ---- same as above command but size will
be in human readable forms
4 )ls -F ---- marks all executables with * and
directories with /
5 )ls —color ---- shows a coloured listing of files
6 )ls -a ---- shows all files in the present directory
including special dot files
Copying Files And Directories
*****************************
1 )cp <file1> <file2> ====> copy file1 to file2
2 )cp <file1> <dirname> ====> copy file1 to directory dirname
3 )cp -r <dirname1> <dirname2> ====> copy dirname1 directory to dirname2
directory recursively
Renaming And Moving Files
*************************
1 )mv <oldname> <newname> ---- renames file with old name to new
name
2 )mv <olddir> <newdir> ---- renames directory with olddir to
newdir
3 )mv <filename> <dirname> ---- moves file to the directory
Removing Files
**************
1 )rm <filename> ====> removes file with old name to new name
2 )rmdir <dirname> ====> removes empty directory dirname
3 )rmdir -rf <dirname> ====> removes a non empty directory
Some More Useful Commands
*************************
1 )clear ---- clears the terminal screen
2 )locate ---- search for a specified filename
3 )passwd ---- allows to change the password
4 )whoami ---- displays the current logged in user
Getting HELP
***********
1 )man <command name> ====> find out what the command does
2 )man -f <command name> ====> one line summary of what the
command does
3 )man -k <keyword> ====> search for a command with keyword
Directory Structure In Linux (important Files)
**********************************************
File Content
/bin Essential User Command Binaries
/boot Static files of the boot loader
/dev Device files
/etc host specific system configuration
/home user home directories
/lib essential shared libraries and kernel
modules
/mnt mount point for devices
/opt add on application software packages
/sbin system binaries
/tmp temporary files
/usr user utilities and applications
/var variable files
/root home directory of the root user
Executing Files
***************
How to execute a file in linux
cd to the directory which contains the file to e executed
type chmod +x <name_of_file>
type ./<name_of_file>
System Shutdown Commands
************************
1 ) halt ---- Brings the system down immediately
2 ) init 0 ---- Powers off the system using predefined scripts to synchronize and clean up the system prior to shutting down
3 ) init 6 ---- Reboots the system by shutting it down completely and then restarting it
4 ) poweroff ---- Shuts down the system by powering off
5 ) reboot ---- Reboots the system
6 ) shutdown ---- Shuts down the system
Ip Commands
************
1 ) ip addr show ====> show ip address of a system
2 ) ip addr add 192.168.50.5 dev eth1 ====> assign IP Address to a specific interface
3 ) ip addr del 192.168.50.5/24 dev eth1 ====> remove an assigned IP address from the given interface
4 )# ip route show ====> check the route table information
Result
******
Concepts to linux command has been understood clearly . # experiment
