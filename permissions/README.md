In each excersise I performed the following commands
1. vi [file name] to create the file
2. In the first line I wrote the shebang 
3. In the second line I wrote the script as the list as follow
-------------------------------------------------------
Excersise 0.Create a script that switches the current user to the user betty: su betty
Excersise 1. Write a script that prints the effective username of the current user: whoami
Excersise 2. Write a script that prints all the groups the current user is part of: groups
Excersise 3. Write a script that changes the owner of the file hello to the user betty: 
             chown betty hello

Excersise 4. Write a script that creates an empty file called hello:
Excersise 5. Write a script that adds execute permission to the owner of the file hello. The file
             hello will be in the working directory:
Excersise 6. Write a script that adds execute permission to the owner and the group owner, and read 
             permission to other users, to the file hello. The file hello will be in the working 
             directory:
Excersise 7. Write a script that adds execution permission to the owner, the group owner and the
             other users, to the file hello. The file hello will be in the working directory. You
             are not allowed to use commas for this script:

Excersise 8. Write a script that sets the permission to the file hello as follows:

    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions

Excersise 9. Write a script that sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

    The file hello will be in the working directory
    You are not allowed to use commas for this script

Excersise 10. Write a script that sets the mode of the file hello the same as olleh’s mode.

    The file hello will be in the working directory
    The file olleh will be in the working directory

Excersise 11. Create a script that adds execute permission to all subdirectories of the current
              directory for the owner, the group owner and all other users. Regular files should
              not be changed.

Excersise 12. Create a script that creates a directory called my_dir with permissions 751 in the 
              working directory.
Excersise 13. Write a script that changes the group owner to school for the file hello

    The file hello will be in the working directory
    The script must be present on the github repository and on the sandbox on the folder /tmp

Excersise 14. Write a script that changes the owner to vincent and the group owner to staff for
              all the files and directories in the working directory.
Excersise 15. Write a script that changes the owner and the group owner of _hello to vincent and 
              staff respectively.

    The file _hello is in the working directory
    The file _hello is a symbolic link

Excersise 16. Write a script that changes the owner of the file hello to vincent only if it is owned by the user guillaume.

    The file hello will be in the working directory
-------------------------------------------------------

4. chmod u+x [FILE NAME]
5. ./[FILENAME]
6. git add
7. git commit -m "[DESCRIPTION]"
8. git push 

In tasks 3 / 13 / 14 / 15 / 16 must be done inside the sandbox in order to be corrected by the checker, I pulled in sandbox following the previous steps described.

