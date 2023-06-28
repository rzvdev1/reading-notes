# The Command Line

The command line is a terminal text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text. Within a terminal you have what is known as a shell and is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you.

The basic navigation commands are: the `pwd` command, the `ls` command, the `cd` command, and the `mkdir` command. The `pwd` command will print the working directory. The `ls` command will list the contents of the current directory. The `cd` command will change the current directory. The `mkdir` command will make a new directory. There are 2 types of paths we can use, absolute and relative paths. Absolute paths specify a location (file or directory) in relation to the root directory. Relative paths specify a location (file or directory) in relation to where we currently are in the system.

More about files, this is very important and a common source of problems for people new to Linux. Other systems such as Windows are case insensitive when it comes to referring to files. Linux is not like this. As such it is possible to have two or more files and directories with the same name but letters of different case. Spaces in file and directory names are perfectly valid but we need to be a little careful with them. To access a file with space will be the first approach involves using quotes around the entire item or another method is to use what is called an escape character, which is a backslash ( \ ). To make a file or directory hidden all you need to do is create the file or directory with it's name beginning with a . or rename it to be as such. Likewise you may rename a hidden file to remove the . and it will become unhidden. The command ls which we have seen in the previous section will not list hidden files and directories by default. We may modify it by including the command line option -a so that it does show hidden files and directories.

Manual Pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept. The commands for man is the following:
man \<command>
Look up the manual page for a particular command.
man \-k <search term>
Do a keyword search for all manual pages containing the given search term.
\<term>
Within a manual page, perform a search for 'term'
n
After performing a search within a manual page, select the next found item.

File Manipulation, linux organises it's file system in a hierarchical way. Creating a directory is pretty easy. The command we are after is mkdir which is short for Make Directory. The first one is -p which tells mkdir to make parent directories as needed (demonstration of what that actually means below). The second one is -v which makes mkdir tell us what it is doing (as you saw in the example above, it normally does not). A lot of commands that involve manipulating data within a file have the nice feature that they will create a file automatically if we refer to it and it does not exist. In fact we can make use of this very characteristic to create blank files using the command touch. The command we use for this is cp which stands for copy. To move a file we use the command mv which is short for move. It operates in a similar way to cp. One slight advantage is that we can move directories without having to provide the -r option. As with rmdir, removing a file is an action that may not be undone so be careful. The command to remove or delete a file is rm which stands for remove.

### Resources I use

Linux Tutorial[^1] and cheat sheet[^2]

[^1]: [Linux](https://ryanstutorials.net/linuxtutorial/)
[^2]: [Commands](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
