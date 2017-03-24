wget https://raw.githubusercontent.com/AllGray/guacamole/master/guac-install.sh
chmod +x guac-install.sh
apt-get update
apt-get -y install dos2unix
dos2unix guac-install.sh
./guac-install.sh
