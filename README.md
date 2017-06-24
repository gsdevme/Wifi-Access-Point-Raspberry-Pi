# Wifi-Access-Point-Raspberry-Pi

## Requirements

Check the Wireless Interface connected to the Pi can support `AP` 

```bash
iw list | grep "Supported interface modes" -A 8
```
![image](check-interace-works.png)

## Packages

```bash
sudo apt-get install -y hostapd
```
