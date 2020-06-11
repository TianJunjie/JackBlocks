# HW and SW version
## HW
```
pi@raspberrypi:~ $ cat /proc/device-tree/model
Raspberry Pi 4 Model B Rev 1.2pi
```

## OS
```
pi@raspberrypi:~ $ cat /etc/debian_version 
10.3

pi@raspberrypi:~ $ cat /etc/os-release
PRETTY_NAME="Raspbian GNU/Linux 10 (buster)"
NAME="Raspbian GNU/Linux"
VERSION_ID="10"
VERSION="10 (buster)"
VERSION_CODENAME=buster
ID=raspbian
ID_LIKE=debian
HOME_URL="http://www.raspbian.org/"
SUPPORT_URL="http://www.raspbian.org/RaspbianForums"
BUG_REPORT_URL="http://www.raspbian.org/RaspbianBugs"
```

## Python
```
pi@raspberrypi:~ $ python3 --version
Python 3.7.3

pi@raspberrypi:~ $ pip3 --version
pip 18.1 from /usr/lib/python3/dist-packages/pip (python 3.7)

```

## Python lib
### install
```
pip3 install pylgbst

sudo apt-get install build-essential
sudo apt-get install libglib2.0-dev
pip3 install bluepy

pip3 install pygatt

sudo apt-get install libbluetooth-dev
sudo apt-get install libboost-thread-dev libboost-python-dev
pip3 install gattlib

```

### version
```
bluepy            1.3.0 
pygatt            4.0.5
pylgbst           1.1.2 
gattlib           0.20200122 

```
