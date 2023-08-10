# Linux-project
 
### LINUX COMMANDS

 __MKDIR__ 
 
  __mkdir command__ allows users to create or make new directories.

  
  Create a directory named  __devops__



  `mkdir devops`

![](./images/3.png)





__CD__

  __cd__ command means __change directory__. It is used to change the current directory of the terminal.
 
`cd devops`


  ![](./images/4.png)


__PWD__

__pwd__ means present working directory.The root directory is represented by the first slash / while the last directory named is your __pwd__.

`pwd`
![](./images/5.png)



__LS__

__ls command__ is used to display lists of files and directories in your current working directories.


`ls`
![](./images/9.png)


To display hidden files and directories.The files that start with the dot are hidden (.). The current directory (.) as well as the parent directory (..) 

`ls -a`


![](./images/10.png)


To display complete information about the files in a long listing format.

`ls -l`

![](./images/11.png)

To display File Index Number,for internal purposes you may need to know the index number of a file. 

`ls -i`

![](./images/12.png)

To display the latest time a file was created.

`ls -lt`

![](./images/13.png)

To sort all the files and directory based on the change of time and lists the newest time in reverse order.

`ls -ltr`

![](./images/14.png)


__SUDO__ (super user do)

__sudo__ gives power to a normal user to execute commands which is owned by root user.

`sudo apt update`

![](./images/7.png)

`sudo -i`

![](./images/8.png)

__CAT__

__cat__ means concatenate. To view the contents of a file.

`cat`

![](./images/15.png)

__To view multiple files.__

`cat mydata myfile.txt`

![](./images/16.png)

__To create a new file.__

`cat > library`

![](./images/17.png)


__CP__

__cp__ means copy.It is used for copying files from one location to another.

`cp myfile.txt library`

_library_ is an empty file so i copied the content in _myfile.txt_ to _library_.

![](./images/18.png)


__MV__

__mv__ means move. It moves files and directories from one directory to another.

`mv mydata music`

![](./images/19.png)

__renaming a file or directory__

`mv music mymusic`

_renamed music to mymusic_

![](./images/20.png)







