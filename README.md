This repository contains scripts for installing, updating and uninstalling Akvila.Backend. The scripts simplify the process of managing the server side of AkvilaLauncher, making it easy and convenient to perform the necessary operations. 

## Installation

To install Akvila.Backend, run the following commands in a convenient directory:

```sh
curl -O https://raw.githubusercontent.com/AkvilaLauncher/Akvila.Backend.Installer/master/akvila-installer.sh
chmod +x ./akvila-installer.sh
./akvila-installer.sh
```

## Update

To update the Akvila.Backend, run the following command in the directory where the `docker-compose.yml` and `.env` files are located:

```sh
curl -s https://raw.githubusercontent.com/AkvilaLauncher/Akvila.Backend.Installer/master/akvila-updater.sh | sh
```

## Delete

To remove Akvila.Backend, run the following command in the directory where the `docker-compose.yml` and `.env` files are located:

```sh
curl -s https://raw.githubusercontent.com/AkvilaLauncher/Akvila.Backend.Installer/master/akvila-deleter.sh | sh
```
