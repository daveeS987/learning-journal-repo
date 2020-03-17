# Cheat Sheet

## Choosing a Text Editor
-Pick a text Editor you enjoy using. What matters is if you can get the job done with it. 
-A text editor is software that allows you to write and manage text to build a website. 


#### Important Features to Consider
-code completion  
-syntax highlighting  
-nice variety of themes(to reduce eyestrain and fatigue)  
-able to choose form a healthy selection of extensions


#### Using software that already comes with your computer 
-if you use text editor that comes on your computer, make sure you first create a folder on your computer somewhere to store your entire website
-make sure you have the appropriate extensions at the end of the file names


#### Third Party Options


#### Difference Between Text Editors and IDE's

A text editor edits text, manages it, and manages files. 
An IDE(Integrated Development Environment) is a suite of differetn software all coming together. An IDE is a text editor, a file
manager, a compiler, and a debugger all in one software package.


## The Command Line

pwd - print working directory  
ls : list  

ls [options][locations] Square brackets means they're optional
ls - l: long listing  
ls /etc: When we do this it tells ls not to list our current directory but instead to list that directories contents.  
ls -l /etc: We ran ls with both a command line option and argument. As such it did a long listing of the directory /etc.  
cd - change directory. If you run the command cd without any arguments then it will always take you back to your home directory.
   

#### Paths
Absolute and Relative

Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )

Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

- ~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
- . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
- .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.


#### More about files

Everything is a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc  
file [path]
Linux is case sensitive  
Becareful with spaces in names. Use quotes to fix spaces or a backslash to escape the space
To hide files use a . period before the filename. Use ls -a to show hidden fiels and directories

file : obtain information about what type of file a file or directory is.
ls -a : List the contents of a directory, including hidden files.


+ item 1
+ item 2
+ item 3
