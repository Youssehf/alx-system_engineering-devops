**This readme file is describing what each script is doing.**

File: 0-iam_betty-------->This script switches the current user to the user betty.
File: 1-who_am_i--------->This script prints the effective username of the current user.
File: 2-groups----------->This script prints all the groups the current user is part of.
File: 3-new_owner-------->This script changes the owner of the file hello to the user betty.
File: 4-empty------------>This script creates an empty file called hello.
File: 5-execute---------->This script adds execute permission to the owner of the file hello.
File: 6-multiple_permissions--->This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
File: 7-everybody--------------->This script adds execution permission to the owner, the group owner and the other users, to the file hello
File: 8-James_Bond-------------->This script sets the permission to the file hello as follows:Owner: no permission at all, Group: no permission at all, Other users: all the permissions.
File: 9-John_Doe---------------->This script sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
File: 10-mirror_permissions----->This scripts sets the mode of the file hello the same as olleh’s mode.

The file hello will be in the working directory
The file olleh will be in the working directory
File: 11-directories_permissions---->This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Regular files should not be changed.
File: 12-directory_permissions----->This script creates a directory called my_dir with permissions 751 in the working directory.
File: 13-change_group------------>This script changes the group owner to school for the file hello

The file hello will be in the working directory.
File: 100-change_owner_and_group----->This script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
File: 101-symbolic_link_permissions--->This script  changes the owner and the group owner of _hello to vincent and staff respectively.

The file _hello is in the working directory
The file _hello is a symbolic link
File: 102-if_only--------->This script  changes the owner of the file hello to betty only if it is owned by the user guillaume.

The file hello will be in the working directory
File: 103-Star_Wars--------->This script  that will play the StarWars IV episode in the terminal.






