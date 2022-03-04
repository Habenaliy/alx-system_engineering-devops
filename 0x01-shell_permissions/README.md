su betty  to change the the user to betty
echo "$USER" to print effective username of the current username
groups to see which group does the current user belongs to
chown betty hello to change the file hello's owner to betty
touch hello  to make an empty file named hello
chmod u+x hello to add axcutable permission to the file hello
chmod ug+x,o+r hello to add excutable permssions to the owner and group and read to others
chmod ugo + x hello to add excution permission to all(user,group,other)
chmod 07 hello to deny all permissions to owner and group but grant all to others
chmod 753 to change mode of a file -rwxr-x-wx 1
chmod--reference==olleh hello to make the permission of hello as the same as olleh
su chmod -R +111 */ to add all permissions to the subdirectories
mkdir -m 751 crearin a directory with specified permissions
chgrp school hello to change the group of the file hello to the group school
chown vincent :staff * to change ownership to vincent and change group to staff
chown -h vincent:staff _hello to change the owner and group to acertain file _hello
