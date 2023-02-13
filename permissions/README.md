- su [username] - change user to betty
- id -u -n - print current user name
- groups - print user groups
- chown [username] [file] - change file owner
- touch [filename] - create a new empty file
- chmod u+x [filename] - change execute permission of file
- chmod 754 [filename] - permission to owner and group owner rwxr and other users to r
- chmod 751 [filename] - execution permission to the owner, the group owner and the other users
- chmod 007 [filename] - 
    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions
- chmod 753 [filename] - set file to -rwxr-x-wx
- chmod 664 [filename] - set file to -rw-rw-r--
