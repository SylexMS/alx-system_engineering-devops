# Shell permissions 0x01

## Hi 👋, I'm Sylex

## in this readme i will explain each script is doing

in ```0-iam_betty```, the command ```su betty``` means to switch to user ```betty```.

in ```1-who_am_i```, the coimmand ```whoami``` means to prints the effective username of the current user.

in ```2-groups```, the command ```groups``` means to prints all the groups the current user is part of.

in ```3-new_owner```, the command ```sudo chown betty hello``` means to change the owner of the file ```hello``` to the user ```betty```.

in ```4-empty```, the command ```touch hello``` means to creat the file ```hello```.

in ```5-execute```, the command ```chmod u+x hello``` means to adds execute permission to the owner of the file ```hello```.

in ```6-multiple_permissions```, the command ```chmod ug+x,o+r hello``` means to add execute permission to the owner and the group owner, and add read permission to other users, all this permissions to the file ```hello```.

in ```7-everybody```, the command ```chmod ugo+x hello``` means to add execute permission to the owner, the group owner and other users to the file ```hello```.

in ```8-James_Bond```, the command ```chmod 007 hello``` means to add all permissions to other users to the file ```hello```.

in ```9-John_Doe```, the command ```chmod 753 hello``` means to add all permissions to the owner , add execute & read permissions to the group owner and add execute & write permissions to other users, all this to the file ```hello```.

in ```10-mirror_permissions```, the command ```chmod --reference=olleh hello``` means to sets the mode of the file ```hello``` the same as ```olleh```’s mode.

in ```11-directories_permissions```, the command ```chmod -R +X .``` means to adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

in ```12-More_directories```, the command ```mkdir -m 751 my_dir``` means to creates a directory called ```my_dir``` with permissions 751 in the working directory.

in ```13-change_group```, the command ```chgrp school hello``` means to change the group owner to ```school``` for a the file```hello```.

in ```100-change_owner_and_group```, the command ```chown vincent:staff *``` means to change the owner to ```vincent``` and group owner to ```staff```  for all the files and directories in the working directory.

in ```101-symbolic_link_permissions```, the command ```chown -h vincent:staff _hello``` means to change the owner of the file ```hello``` to ```betty``` only if it is owned by the user ```guillaume```.

in ```102-if_only```, the command ```chown --from=guillaume betty hello``` means to change the owner of the file ```hello``` to ```betty``` only if it is owned by the user ```guillaume```.
