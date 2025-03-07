# MPRO Picons Installation Guide:

This repository contains the ```MPRO.srp-800X450.light.transparant-picon.tar.xz``` file, which is a collection of transparent picons for use with Enigma2-based devices. These picons are optimized for a resolution of 800x450 pixels.

## Installation Instructions:
  - You can install the picons either on an external storage device (e.g., USB drive) or internally on your Enigma2 device. Follow the steps below based on your preferred installation path.
- `NOTE:` if u uploaded MPRO before... u need to remove the old one on follows commands:
+ on `External Storage` ```/media/hdd/```or```/media/usb/``` or ```/media/mmc/``` etc...:
  ```
   rm -r /media/hdd/picon/MPRO
  ```
  + on `internal Storage (inside device)` 
   ```
   rm -r /usr/share/enigma2/picon/MPRO
  ```

## Download the File:
You can download the `MPRO.srp-800X450.light.transparant-picon.tar.xz` file directly from this repository using the `wget` command. Connect to your Enigma2 device via Telnet and run the following command:

```
wget https://github.com/MOVICAMPRO/picons/raw/main/MPRO.srp-800X450.light.transparant-picon.tar.xz -O /tmp/MPRO.srp-800X450.light.transparant-picon.tar.xz
```
- for 400x240:
  ```
  wget https://github.com/MOVICAMPRO/picons/raw/refs/heads/main/MPRO.srp-400X240.light.transparant-picon.tar.xz -O /tmp/MPRO.srp-400x240.light.transparant-picon.tar.xz
  ```
### Option 1: Install on External Storage (```/media/hdd/```):

- NOTE: if u have ```/media/usb/``` or ```/media/mmc/``` etc... make it instead of ```/media/hdd/```

**1. Extract the File:**

  ```
  tar -xvf /tmp/MPRO.srp-800X450.light.transparant-picon.tar.xz -C /media/hdd/
  ```
- for 400x240:
    ```
  tar -xvf /tmp/MPRO.srp-400x240.light.transparant-picon.tar.xz -C /media/hdd/
    ```

**2. symlink MPRO picons:**

  ```
  ln -s /media/hdd/picon/MPRO/* /media/hdd/picon/
  ```

 + if u dont want symlink put this command:
   ```
   mv /media/hdd/picon/MPRO/* /media/hdd/picon/ && rm -r /media/hdd/picon/MPRO
   ```
### Option 2: Install Internally (```/usr/share/enigma2/```):

**1. Extract the File:**

  ```
  tar -xvf /tmp/MPRO.srp-800X450.light.transparant-picon.tar.xz -C /usr/share/enigma2/
  ```
- for 400x240:
    ```
    tar -xvf /tmp/MPRO.srp-400X240.light.transparant-picon.tar.xz -C /usr/share/enigma2/
    ```

**2. symlink MPRO picons:**

  ```
  ln -s /usr/share/enigma2/picon/MPRO/* /usr/share/enigma2/picon/
  ```
 + if u dont want symlink put this command:
   ```
   mv /usr/share/enigma2/MPRO/* /usr/share/enigma2/picon/ && rm -r /usr/share/enigma2/MPRO
   ```
### Notes

  + Picons are used to display channel logos on your Enigma2 device. Ensure that your skin supports picons for them to appear correctly.


___________________________________________________________________________________________________________

 __ENJOY...__
