## rkdeveloptool
Used to pull images and push images on the ASIAIR Mini/Plus RockChip

### Install the default apps to compile application
```	
sudo apt-get install libudev-dev libusb-1.0-0-dev dh-autoreconf build-essential git
```
### Download repository
```	
git clone https://github.com/open-astro/rkdeveloptool.git
```	
### Change the directory to rkdevloptool and run commands
```
cd rkdeveloptool
aclocal
autoreconf -i
autoheader
automake --add-missing
./configure
make
```
### Run tool commands
```
rkdeveloptool -h
```
