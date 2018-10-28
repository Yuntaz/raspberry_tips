# Install Mac Changer
This utility will let us to fake the mac address of a device.

```
sudo apt-get install macchanger macchanger-gtk
```

## Requeriments
If you are connected via ssh be careful to shutdown the inteface and change the macaddress. You need to choose a device that you are not using to be connected using ssh.

## Commands

### Check a device
```
sudo macchanger eth0
```

### Shutdown interface
```
sudo ifconfig eth0 down
```
### Change macaddress
```
sudo macchanger -m 8C:DC:D4:0E:D3:B4 eth0
```
### Startup interface
```
sudo ifconfig eth0 up
```
### Reset to original mac address of the interface
```
sudo macchanger -p interface
```
