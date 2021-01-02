# Checks
List your USB devices to see if the UPS is connected.
```
lsusb
```
Ex. mine shows up as the following:
```
Bus 003 Device 004: ID 0764:0501 Cyber Power System, Inc. CP1500 AVR UPS
```
# Software
Install the CyberPower PowerPanel Personal package. 
```
wget https://dl4jz3rbrsfum.cloudfront.net/software/PPL-1.3.3-64bit.deb
sudo dpkg -i PPL-1.3.3-64bit.deb
```
# Testing
This command will test the UPS and the shutdown function.
```
sudo pwrstat -test
```
# Adjusting Shutdown


# References
https://www.cyberpowersystems.com/product/software/power-panel-personal/powerpanel-for-linux/
