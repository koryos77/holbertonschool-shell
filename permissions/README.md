0_ sudo - <username> to switch the current user to another one
1_ whoami to print de current username
2_ id -Gn to print all the groups the current user is part of 
3_ chown user file to change the owner of a file
4_ touch to create a file
5_ chmod user+x filename to add execute permission to a user 
6_ chmod 754 filename to add execute permission to user, group owner and read only for others
7_ chmod a+x filename to add execute permission to everyone
8_ chmod 007 filename to give permission only to others
9_ chmod 753 file name to give -rwxr-x-wx
10_ chmod --reference=<newFile> <originFile>
11_ chmod -R a+x */ to give owners, groups and others executions for all subsdir
12_ mkdir -m 751 my_dir to make a dir called my_dir with permissions 751 in the working dir
13_ chgrp to change the group owner
14_ chown -R user:group to change the owner and the group owner of all dir
15_ chown -h user:group symlinkName to change owner and the group owner of a symlink
16_ chown --from=owner new_owner filename to change an owner if only option