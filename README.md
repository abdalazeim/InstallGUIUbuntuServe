# How to Install a GUI on Ubuntu Server: Step-by-Step Guide

### Prerequisites
### Before proceeding with the installation, ensure that you have the following:
### 1- The latest Ubuntu Server installed.
### 2- A user account with sudo privileges.
### 3- An active internet connection..
### Installing a graphical user interface (GUI) on the Ubuntu server
## 1. Step 1: Update your system
#  sudo apt update && sudo apt upgrade
## 2. Step 2: Install the desktop environment
# sudo apt install ubuntu-desktop -y
## 3. Installing Xfce the following command:
# sudo apt install xubuntu-core -y
## 4. Installing other desktopsn with the following command:
# sudo apt install lubuntu-core -y
# sudo apt install kubuntu-desktop -y
## 5. IInstall a display manager
# sudo apt install lightdm -y
## 6. Enable GUI to start automatically
# systemctl get-default
## 7. By default, it should return multi-user.target, which is the non-graphical mode. To switch to graphical mode, run:
# sudo systemctl set-default graphical.target
## 8.Reboot the system
## sudo reboot






### That's All:
### - Thanks For Usage :)
 ### - Have A Nice Day,GoodBye :)
### >>>>>>> Stashed changes

