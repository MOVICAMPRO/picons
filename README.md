# MPRO Picons Installation Guide:

This repository contains the ```MPRO.srp-800X450.light.transparant-picon.tar.xz``` file, which is a collection of transparent picons for use with Enigma2-based devices. These picons are optimized for a resolution of 800x450 pixels.

## Installation Instructions:
You can install the picons either on an external storage device (e.g., USB drive) or internally on your Enigma2 device. Follow the steps below based on your preferred installation path.

## Download the File:
You can download the `MPRO.srp-800X450.light.transparant-picon.tar.xz` file directly from this repository using the `wget` command. Connect to your Enigma2 device via Telnet and run the following command:

```
wget https://github.com/MOVICAMPRO/picons/raw/main/MPRO.srp-800X450.light.transparant-picon.tar.xz -O /tmp/MPRO.srp-800X450.light.transparant-picon.tar.xz
```
### Option 1: Install on External Storage (```/media/hdd/```):

- NOTE: if u have ```/media/usb/``` or ```/media/mmc/``` etc... make it instead of ```/media/hdd/```

**1. Extract the File:**

  ```
  tar -xvf /tmp/MPRO.srp-800X450.light.transparant-picon.tar.xz -C /media/hdd/
  ```

**2. symlink MPRO picons:**

  ```
  ln -s /media/hdd/picon/MPRO/* /media/hdd/picon/
  ```
### Option 2: Install Internally (```/usr/share/enigma2/```):

**1. Extract the File:**

  ```
  tar -xvf /tmp/MPRO.srp-800X450.light.transparant-picon.tar.xz -C /usr/share/enigma2/
  ```

**2. symlink MPRO picons:**

  ```
  ln -s /usr/share/enigma2/picon/MPRO/* /usr/share/enigma2/picon/
  ```
### Notes

  + Picons are used to display channel logos on your Enigma2 device. Ensure that your skin supports picons for them to appear correctly.


___________________________________________________________________________________________________________

 __ENJOY...__
