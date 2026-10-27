## Unreleased ##

- Created script "0-iam_betty". When run, this script will change the current user to "betty".
- Created script "1-who_am_i". When run, this script will print the name of the current user.
- Created script "2-groups". When run, this script will pring the names of all groups assigned to the user.
- Created script "3-new_owner". When run, this script will change the owner of file "hello" to the user "betty".
- Created script "4-empty". When run, this script will create an empty file called "hello".
- Created script "5-execute". When run, this script update the file "hello" with execute persmissions for the owner.
- Created script "6-multiple_permissions". When run, this script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
- Created script "7-everybody". When run, this script adds execution permission to the owner, the group owner and the other users, to the file hello.
- Created script "8-James_Bond". When run, this script sets the permission to the file hello to 007.
- Created script "9-John_Doe". When run, this script sets the mode of the file hello to -rwxr-x-wx.
- Created script "10-mirror_permissions" When run, this sctipt copys the permissions of the referenced file.
- Created script "11-directories_permissions". When run, this script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
- Created script "12-directory_permissions". When run, this script creates a directory called my_dir with permissions 751 in the working directory.
