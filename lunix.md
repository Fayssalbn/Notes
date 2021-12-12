# Essential Linux commands

## ls command

The ls command lists the directory content. If no directory is specified, the command will display the content of the working directory.

```bash
#!/bin/bash
fenix@fenix-sv:~$ ls
```

## pwd command

The pwd command is used to print the path of the current directory.

```bash
#!/bin/bash
fenix@fenix-sv:~$ pwd
```

## mkdir command

To create a new directoy, the mkdir command is used. You must specify the name of the directory. If no path is specified, the directory is created inside the working directory.

```bash
#!/bin/bash
fenix@fenix-sv:~$ mkdir **file name**
```

## whoami command

The whoami command displays the username of the current user.

```bash
#!/bin/bash
fenix@fenix-sv:~$ whoami
```

## cd command

To change the current working directory we use the cd command. You must specify the path of the directory you would like to access.

```bash
#!/bin/bash
fenix@fenix-sv:~$ cd
```

```bash
#!/bin/bash
fenix@fenix-sv:~$ wget -p 127.0.0.1:8080
```

## gzip command

You can compress any file from Terminal window using gzip **file name** command but it will remove original file from the directory. If you wish to keep the original file then use gzip -k **file name** instead as it will keep both original as well as new compressed file in the directory.

## whatis

If you wish to know for what the particular Linux command can be used for then just execute the command whatis **command name** in Terminal shell and it will show you short one line description of that particular Linux command.

## who

This one is for system administrators who handle and manage various users on Linux system. who command when executed in Terminal show the complete list of those users who are currently logged into Linux system.

## w

w is the short and simple command which will help you view the list of currently logged in users.

## top

top is simple but useful command to monitor all the ongoing processes on the Linux system with the user name, priority level, unique process id and shared memory by each task.

## passwd

You can use passwd command to change the password for self or any user, just through the command passwd if you want to change password for youself and passwd **user name** if you want to change password for particular user.

## history

When fired into Terminal shell, history command will list all the commands used by you in serial numbered form. Using exclamation mark ! and serial number of the command will help you execute that particular command without need to writing whole command in the terminal

## login

If you want to switch user or want to create new session then fire this command in Terminal window and provide the details like login id and password as shown in screenshot below.

## mv

mv (move) command can be used to move one file or directory to another file or directory. It is very useful command especially when you’re working on system administration.

## ps

If you want to see the list of processes that are currently running for your session or for other users on the system then ps command is for you as it shows processes with their process identification numbers and in detail as well when you use ps -u command.

## kill

You can use this command to kill the currently ongoing processes manually form the Terminal shell itself. You need unique PID i.e. process identification number to kill the process.

## rm

rm **file name** command can be used to remove any file from the working directory. For better convenience you can use rm -i **file name** command as it will first ask for your confirmation before removing the file.

## ifconfig

ifconfig is another useful Linux command which can be used to configure network interface on the system.

## clear

clear is simple command for Linux Terminal shell, when executed it will clear the Terminal window for fresh start.

## su

su **username** command can be used to switch to another account right from the Linux Terminal window.

## wget

wget **file path** is very useful command to download any file from the internet and best part is download works in background so that you can continue working on your task.

## zip

You can use zip command to compress one or more files as you can see in the screenshot below. It is simple but useful command to compress any number of files in a go.

## unzip

To extract files from compressed zip file use unzip **file name** command in Terminal shell. You can also use this command to extract files from multiple compressed files from the particular directory.

## shutdown

You can use shutdown command to turn of the system directly from Terminal shell. This command will shutdown the system exactly one minute after being executed. You can use shutdown -c command to cancel shutdown.

## dir

dir (directory) command can be used to view the list of all directories and folders present in current working directory.

## cd

cd command helps you to access particular directory or folder from the file system. You can also use cd .. command to go back to root.

## reboot

As the name suggests you can use reboot command to restart or shutdown the system from the Terminal window. There are several options available with this command as you can see in following screenshot.

## sort

sort **file name** command will help you sort file or arrange any record in particular order generally according to their ASCII values.

## service

service command will display results of System V init scripts in the Terminal window. You can view the status of particular service or all the services as shown in below screenshot.

## ssh

ssh acronym for Secure Shell is protocol which is used to securely connect to host system. ssh username@host**IP/Domain Name** is the command to connect to host computer as a user.

## useradd

useradd [optaons] login command will help you add user account into your system

## userdel

userdel [option] login command will let you delete any user account from the system.

## usermod

Using usermod [options] login command you can modify any user account present on the system.
