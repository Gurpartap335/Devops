Users and Groups :
In any traditional operating system , there are uses and groups .
They exit solely for access and permissions .
File access and ownership is also permission dependant .

The system uses user ids (UID) to manage users .
The system also uses groups to manage permissions groups , groups are just sets of users with permission 
set by that group , they are identified by the system with their group ID (GID).

In Linux, you'll have users in addition to the normal humans that use the system. 
Sometimes these users are system daemons that continuously run processes to keep
the system functioning .

Root or superuser is the most powerful user on the system .


you need root permission to view this file : /etc/shadow


root :
to enter superuser mode : su -i

/etc/sudoers this file lists users who can run sudo .
you can edit this file with the visudo command .

/etc/passwd

to find out what users are mapped to what ID , look at the /etc/passwd file .

root:x:0:0:root:/root:/bin/bash

1. username
2. user password : encrypted user passwords .
x :  password is stored in /etc/shadow file .
a : means the user does not have login access and if there is a blank field that means the user does not have a password .
3. The user ID - as you can see root has the UID of 0
4. The group ID
5. GECOS field - This is used to generally leave comments about the user or account such as their real name or phone number, it is comma delimited.
6. User's home directory
7. User's shell - you'll probably see a lot of user's defaulting to bash for their shell


/etc/shadow 
file is used to store information about user authentication .

root:Myjfdjfkr3r:15:0:999:7:::

username
encrypted password .
date of last password changed
minimum password age
maximum password age
password warning period
password inactivity period
account expiration date
reserved field for forture use .

Another file that is used in user management is the /etc/group file. 
This file allows for different groups with different permissions.


User management tools :

useradd
userdel -r 

passwd


