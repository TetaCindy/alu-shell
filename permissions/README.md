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
This script adds execute permission to the owner and group, and read permission to others for the file `hello` using `chmod u+x,g+x,o+r`.

