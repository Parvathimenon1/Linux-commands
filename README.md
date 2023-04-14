# Linux-commands

 **Directories**

The folder system in Linux is referred to as directories.
A directory is a file whose sole purpose is to store file names and the information that goes with them. 
Some of them are -
/dev - Contains special files for I/O devices.
/etc - Contains files for system initialization and system management.
/home - Contains login directories for the system users.
/tmp - Contains files that are temporary and are automatically deleted after a specified number of days.
/usr - Contains the lpp, include, and other system directories.
/usr/bin - Contains user-executable programs.

 **Commands and its working**

present working directory
- Command : pwd 
To know the contents in that directory
- Command : ls 
To create a directory
- Command : mkdir <directory name> 
TO offers several ways to navigate and change the working directory using the terminal window
- Command : cd <file name> 
To create a file named "file 1" with no details or content
- Command : touch file 1 
To create a file named "file 1" and can give the content
- Command : cat file 1 or VI file 1 
To move back to the previous directory
- Command : cd.. 
To copy a file to the same directory  in linux
- Command : cp
            cp filename newfilename  
To copy a file to another directory  in linux
- Command : cp filename/ location
To remove or delete files
- Command : rm filename
To delete from a particular directory
- Command : directory name rm filename
To create a folder in a particular folder
- Command : cd dir name
            mkdir new dir name
To move a file to another directory
- Command : mv
            mv filename directoryname/newfilename
To rename a file
- Command : mv
            mv filename newfilename
To search a particular word from the given file
- Command : grep
            grep word filename

**Creating,editing and saving file**
1. pwd
2. cd location
3. cat file name, provide the text
4. cntrl+z => save
5. gedit filename =>to edit text


**Creating multiple users and setting password**
- Command : sudo useradd 'username'
            sudo passwd  'xxxxx'
            To change password
            New password :
            Retype new password : 

**File permission**
To view the permissions given for the file

1. open a directory
   eg : desktop ls -l
   => -rwrw-rw-r--
   => drwxrwxr-x
- = - indicates that it is a file
d = d indicates that it is a directory
r = read
w = write
x = execute
To change permissions
- Command : chmod

- eg : assume u => user
            g => group
            o => other people

     Desktop chmod o+w file 1 (permission to write)
     Desktop chmod g+r file 1 (permission to read)
To remove the permission
- eg : Desktop chmod o-w file 1



 
