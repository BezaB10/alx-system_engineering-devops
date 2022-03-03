This directory contains **shell permissions**\n
**0-iam_betty** switches the current user to the user *betty*.\n
**1-who_am_i** prints the effective username of the current user.\n
**2-groups** printes all the groups the current user is part of.\n
**3-new_owner** changes the owner of the file *hello* to the user *betty*.\n
**4-empty** creates an empity file called 8hello*.\n
**5-execute** adds execute permission to the owner of the file *hello*.\n
**6-multiple_permissions** adds execute permission to the owner and the group owner, and read permission to other users to the file *hello*.\n
**7-everybody** adds execute permission to the owner, the group owner and the other users, to the file *hello*.\n
**8-James_Bond** sets the permission to the file *hello* as, **Owner**:no permission, **Group**:no permission, **Other users**:all the permission.\n
**9-John_D0e** sets the mode of the file *hello* to *-rwxr-x-wx 1 julien julien 23 sep 20 14:25 hello*\n
**10-mirror_permissions** sets the mode of the file *hello* the same as *olleh*'s mode.\n
**11-directories_permissions** adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.\n
**12-directory_permissions** creates a directory called *my_dir* with permissions 751 in the working directory.\n
**13-change_group** changes the group owner to *school* for the file *hello*.\n
