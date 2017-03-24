wget https://raw.githubusercontent.com/AllGray/guacamole/master/guac-chip-install.sh
chmod +x guac-chip-install.sh
apt-get -y install dos2unix jq
dos2unix guac-chip-install.sh
./guac-chip-install.sh


After the installation is finished, go to your.local.ip.address:8080
Log in with the default guacadmin/guacadmin and set it up

Note: First time setup, make two connections, even if one of them is a null connection
The reason for this, is that if you only have one connection, it connects to that 
automatically on every login, and makes it a pain to get back to to control panel.

