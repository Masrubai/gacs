# GenieACS x Ubuntu Server v.22.04
This is autoinstall GenieACS For ubuntu version 22.04 (Jammy)

Requirement Hardware
- Ram 1GB minimal
- SSD 20GB
- CPU 2 Core

Requirement Operating System
- Ubuntu server 22.04
- LibSSL1, NodeJS, NPM, MongoDB
- Konfigurasi mongo+genieACS otomatis
- Konfigurasi service otomatis on reboot startup OS


Auto instalation steps, save & runing gacs
```sh
wget -O - https://raw.githubusercontent.com/Masrubai/gacs/refs/heads/main/gacs-install.sh | bash
```

## Manual Usage
```
sudo su
git clone https://github.com/masrubai/gacs
cd gacs
chmod +x gacs-install.sh
sudo apt-get install dos2unix
dos2unix gacs-install.sh
bash gacs-install.sh
```

