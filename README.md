# GenieACS Ubuntu 22.04
Script autoinstall GenieACS For ubuntu version 22.04 (Jammy) & 

# Installation
```
sudo su
```
Ubuntu 22.04 (Jammy)
```
wget https://raw.githubusercontent.com/abmujib/genieacs-install/main/gacs-jammy-install.sh
```
STB Armbian (Bookworm)
```
wget https://raw.githubusercontent.com/abmujib/genieacs-install/main/gacs-armbian-bookworm.sh
```
```
chmod +x gacs-jammy-install.sh
```
```
sudo apt-get install dos2unix
```
```
dos2unix gacs-jammy-install.sh
```
```
bash gacs-jammy-install.sh
```


# Download SSL
```
wget http://ports.ubuntu.com/pool/main/o/openssl/openssl_1.1.1f-1ubuntu2_arm64.deb
```
```
wget http://ports.ubuntu.com/pool/main/o/openssl/libssl-dev_1.1.1f-1ubuntu2_arm64.deb
```
```
wget http://ports.ubuntu.com/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2_arm64.deb
```

# Install SSL
```
sudo dpkg -i openssl_1.1.1f-1ubuntu2_arm64.deb
```
```
sudo dpkg -i libssl-dev_1.1.1f-1ubuntu2_arm64.deb
```
```
sudo dpkg -i libssl1.1_1.1.1f-1ubuntu2_arm64.deb
```

# Install MongoDB
```
apt-get install mongodb-org=4.4.8 mongodb-org-server=4.4.8 mongodb-org-shell=4.4.8 mongodb-org-mongos=4.4.8 mongodb-org-tools=4.4.8
```
