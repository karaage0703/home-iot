# home-iot
Home Internet of Things

# Setup


## Hardware
### Parts List
- Raspberry Pi 2 or 3
- irMagician
### Devices
- iPhone(iOS 10 over)
- Air Conditioner Remote Controller(Fujitsu AR-RCG1J)
- Light Remote Controller(Koizumi KRU-MRH-7C1)

## Software
- Install Raspbian Jessie (Release date:2016-11-25)
- Install Homebridge
### Install Homebridge
Execute following commands for installing library for homebridge:
```sh
$ sudo apt-get install libavahi-compat-libdnssd-dev
```
Execute following command for installing node.js:
```sh
$ wget https://nodejs.org/dist/v4.3.2/node-v4.3.2-linux-armv6l.tar.gz 
$ tar -xvf node-v4.3.2-linux-armv6l.tar.gz 
$ cd node-v4.3.2-linux-armv6l
$ sudo cp -R * /usr/local/
```
Execute following commands for installing homebridge/homebridge-cmd:
```sh
$ sudo npm install -g homebridge
$ sudo npm install homebridge-cmd -g
```

# Usage
## Clone repository
```sh
$ cd
$ git clone https://github.com/karaage0703/home-iot
```
## Copy conf file
```sh
$ cp ~/home-iot/conf/conf.json ~/.homebridge/conf.json
```

# Test
Execute following command:
```
$ homebridge
```

# Authors
netbuffalo(irmcli.py)

# References
https://github.com/netbuffalo/irmcli
