Learning user permissions scripts
0-iam_betty switches current user to betty
1-who_am_i prints the name of the active user
2-groups prints the groups the user belongs to
3-new_owner changes the owner of the file hello to the user betty
4-file creates an empty file named hello
5-execute adds execute permission to the owner of the hello file
6-multiple_permissions changes permissions of the file to execute for owner and group owner, read for other users
7-everybody gives executable permission to owner, group owner and other users
8-James_Bond removes permissions for owner and group owner, sets all permission to other users
9-John_Doe sets permissions as so : -rwxr-x-wx
10-mirror_permissions mirrors hello file permissions on olleh file permissions
11-directories_permissions sets subdirectories permissions to execute for all users
12-directory_permissions creates a new my_dir directory with 751 permissions
13-change_group changes group owner of hello file to school
