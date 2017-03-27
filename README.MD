wget https://raw.githubusercontent.com/AllGray/guacamole/master/guac-chip-install.sh  
chmod +x guac-chip-install.sh  
sudo ./guac-chip-install.sh  


After the installation is finished, go to your.local.ip.address:8080/guacamole
Log in with the default guacadmin/guacadmin and set it up

Note: First time setup, make two connections, even if one of them is a null connection
The reason for this, is that if you only have one connection, it connects to that 
automatically on every login, and makes it a pain to get back to to control panel.  

You can read more about Guacamole here: https://guacamole.incubator.apache.org/  
If you want a more indepth install guide, you can find that here: https://bbs.nextthing.co/t/chips-and-guacamole-server-tutorial/15840

