# MPRO Picons Installation Guide:

This repository contains the ```MPRO.srp-800X450.light.transparant-picon.tar.xz``` file, which is a collection of transparent picons for use with Enigma2-based devices. These picons are optimized for a resolution of 800x450 pixels.

## Installation Instructions:
You can install the picons either on an external storage device (e.g., USB drive) or internally on your Enigma2 device. Follow the steps below based on your preferred installation path.

## Download the File:
You can download the `MPRO.srp-800X450.light.transparant-picon.tar.xz` file directly from this repository using the `wget` command. Connect to your Enigma2 device via Telnet and run the following command:

```
wget https://github.com/MOVICAMPRO/picons/blob/main/MPRO.srp-800X450.light.transparant-picon.tar.xz -O /tmp/MPRO.srp-800X450.light.transparant-picon.tar.xz
```
### Option 1: Install on External Storage (```/media/hdd/```):

**1. Extract the File:**

  ```
  tar -xvf /tmp/MPRO.srp-800X450.light.transparant-picon.tar.xz /media/hdd/
  ```
**2. Verify Installation:**

  + After extraction, ensure that the picon folder is created in ```/media/hdd/```.

**3. Restart your Enigma2 device or GUI to apply the changes.**
### Option 2: Install Internally (```/usr/share/enigma2/```):

**1. Extract the File:**

  ```
  tar -xvf /tmp/MPRO.srp-800X450.light.transparant-picon.tar.xz /usr/share/enigma2/
  ```
**2.Verify Installation:**
  + After extraction, ensure that the picon folder is created in ```/usr/share/enigma2/```.

**3. Restart your Enigma2 device or GUI to apply the changes.**

## Notes
  + If the picon folder already exists in the target directory, the extraction process will overwrite the existing files. Make sure to back up any important data before proceeding.

  + Picons are used to display channel logos on your Enigma2 device. Ensure that your skin supports picons for them to appear correctly.




__cheers :)__
