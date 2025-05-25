# Shell Permissions Scripts

## 0-iam_betty
This script switches the current user to the user 'betty' using the `su` command 
[200~## 1-who_am_i
This script prints the effective username of the current user using the `whoami` command.
## 2-groups
This script prints all the groups the current user is a member of using the `groups` command.
## 3-new_owner
This script changes the owner of the file `hello` to the user `betty` using the `chown` command.
## 4-empty
This script creates an empty file named `hello` using the `touch` command.
## 5-execute
This script adds execute permission to the owner of the file `hello` using `chmod u+x` .
## 6-multiple_permissions
This script adds execute permission to the owner and group, and read permission to others for the file `hello` using `chmod u+x,g+x,o+r`.## 7-everybody
This script adds execute permission to the owner, group, and others using `chmod a+x` (without using commas).
## 8-James_Bond
This script sets the permissions of the file `hello` so that only others have all permissions (read, write, execute) using `chmod 007`.
## 9-John_Doe
This script sets the mode of the file `hello` to `-rwxr-x-wx` using `chmod 753`, without using commas.
i## 10-mirror_permissions
This script sets the permissions of the file `hello` to be exactly the same as those of `olleh`, using `chmod --reference=olleh hello`.
## 11-directories_permissions
This script adds execute permission for owner, group, and others to all directories in the current directory using `find` and `chmod`, without affecting regular files.
## 12-directories_permissions_more
This script creates a directory called `my_dir` with permissions set to 751 (rwxr-x--x) using `mkdir -m`.
## 13-change_group
This script changes the group owner of the file `hello` to `school` using the `chgrp` command.
## 14-change_owner_and_group
This script changes both the owner and group of all files and directories in the current working directory to `vincent` and `staff`, using `chown vincent:staff *`.
## 15-symbolic_link_permissions
This script changes the owner and group of the symbolic link `_hello` (not its target) to `vincent` and `staff` using `chown -h`.

