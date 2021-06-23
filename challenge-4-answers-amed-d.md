## a) What are the different layers of Linux?
	- Hardware Layer
	- Kernel 
	- Shell
	- Utilities



## b) Explain briefly about three popular Linux shells?
	- Bash (bourne-again shell) 
		- default shell in most linux distributions
		- developed from the original UNIX Bourne Shell
		- unlimited command history
		- contains job control mechanisms to deal with cron jobs specifically
	-  Zsh (z-shell)
		- modern day shell designed to be innovative and interactive. 
		- offers scripting features and is customizable, easy-to-use, and offers auto command completion, spelling correction. 
	- Ksh (korn shell)
		- ctrl+z tweak that can quickly stop a running job
		- contains various advanced features for fast-paced executions
		- includes advanced command-line editing features to edit commands more easily.
		
		

## c) What is the command used to get a guide on how to use a command?
	-man or -h



## d) How to get a list of currently running processes and resource utilization in Linux?
	top -i



## ) What is a pipeline operator in Linux?
	the pipeline operator (" | ") lets you use multiple commands together. allowing the user to use the output from 
	the first command in the next command.



## f) Explain file permission in Linux. How to change it?
	file permissions are parameters set within the kernal of the operating system allowing certain users access to 
	certain files. some files will require admin access while other files may allow you to access them but read only, 
	not allowing any modifications.  


## g) What is the process in a Linux context?
	a process in linux is an instance of a running program, and identified by a PID (process id).



## h) What are Regular Expressions(regex)? What is the meaning of *,+,? In regular expression?
	Regular Expressions are strings representing a pattern to be matched in a search operation 
	(similar to what the program renamer would do without a gui) 



## i) What is a sed command?
	sed is a streamline text editor that helps a user edit and display text from a file. a hybrid of 
	using cat while being able to edit what will be displayed without saving it. using the -i flag will 
	save those changes to the file. 



## j) What is the difference between Hard Link and Soft Link?
	a soft link is similar to a shortcut where the shortcut to an app such as photoshop for example would lead the user, when clicked, would open the app from the original / source file location such as C:\Program Files\Adobe\Adobe Photoshop 2021.exe



## k) What are Daemons?
	daemons are service processes / background processes that run in the background and supervises the system or provides functionality to other processes. *Shell scripts stored in /etc/init.d directory are used to start and stop daemons.*



## l) Explain different file system types in Linux?
	a filesystem is a type of structure that the computer uses to manage and provide space for storage data.



## m) What are some of the major differences between these?
	For example EXT stands for Extended File System and it has many variations such as EXT2, EXT3, and EXT4 which all have their own properties and uses. Some file system types maybe backwards compatible with others and some will have features others dont. 



## n) What is the difference between init.d and systemd?
	The init is a daemon process which starts as soon as the computer starts and continues running until it is shutdown. Init is represented by the "PID=1". Systemd is a system management daemon, similar to init, systemd is the parent of all other processes directly or indirectly and is the first process that starts at boot hence typically assigned a "PID=1". the init process starts serially, and often resulted into delayed and long booting time. systemd was not designed for speed but for getting things done neatly which in turns avoid all the unnecessary delay. 



## o) Name 10 of the most useful CLI commands
	- cd
	- ls
	- cat
	- rm
	- mkdir
	- ifconfig
	- curl
	- ping 
	- grep
	- ps

