# 0x01 - Shell Permissions

### 0-iam_betty
Script that switches the current user to the user betty

### 1-who_am_i
Script that prints the effective username of the current user.

### 2-groups
Script that prints all the groups the current user is part of.

### 3-owner
Script that changes the owner of the file `hello` to the user `betty`

### 4-empty
Script that creates an empty file called hello

### 5-execute
Script that adds execute permission to the owner of the file hello

### 6-multiple permissions
Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

### 7-everybody
Script that adds execution permission to the owner, the group owner and the other users, to the file hello

### 8-James_Bond
Script that sets the permission to the file hello as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions

### 9-John_Doe
Script that sets the mode of the file hello to this:
`
	rwxr-x-wx 1 me me 23 Sep 20 14:25 hello
`

### 10-mirror_permissions
Script that sets the mode of the file hello the same as olleh’s mode.
- The file hello will be in the working directory
- The file olleh will be in the working directory

### 11-directories_permissions
Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Regular files should not be changed.

### 12-directory_permissions
Create a script that creates a directory called my_dir with permissions 751 in the working directory.

### 13-change-group
script that changes the group owner to school for the file hello
- The file hello will be in the working directory
