# Introduction
Useful stuff for Raspberry

# Enabling SSH
After installing Raspbian, the first thing you will try is to SSH to your device. You need to activate the SSH and the VNC interface. 
Here is the list to do it: [https://stackoverflow.com/questions/41318597/ssh-connection-refused-on-raspberry-pi](https://stackoverflow.com/questions/41318597/ssh-connection-refused-on-raspberry-pi)

## From the desktop

* Launch Raspberry Pi Configuration from the Preferences menu
* Navigate to the Interfaces tab
* Select Enabled next to SSH and VNC
* Click OK

# Update Raspberry Pi packages
Please ensure your installed packages are up to date. Raspbian is based on Debian so you need use apt-get to update and install packages.

```
sudo apt-get update
```
