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
