# GenieACS Autoinstall Script
Script autoinstall GenieACS For Ubuntu version 22.04 (Jammy) & STB Armbian (Bookworm)

Armbian 25.5.0-trunk.256_Aml-s9xx-box_bookworm_current_6.12.19 [download](disini)

# Installation
```
sudo su
```
```
sudo apt-get install dos2unix
```
# Ubuntu 22.04 (Jammy)
```
wget https://raw.githubusercontent.com/abmujib/genieacs-install/main/gacs-jammy-install.sh
```
```
chmod +x gacs-jammy-install.sh
```
```
dos2unix gacs-jammy-install.sh
```
```
bash gacs-jammy-install.sh
```
# STB Armbian (Bookworm)
```
wget https://raw.githubusercontent.com/abmujib/genieacs-install/main/gacs-armbian-bookworm.sh
```
```
chmod +x gacs-armbian-bookworm.sh
```
```
dos2unix gacs-armbian-bookworm.sh
```
```
bash gacs-armbian-bookworm.sh
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
