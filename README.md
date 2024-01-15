## rkdeveloptool
Used to pull images and push images on the ASIAIR Mini/Plus RockChip

### Install the default apps to compile the application
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
### Run help tool commands
```
./rkdeveloptool -h
```

> [!TIP]
>  You will need a USB Type-C to USB-A 2.0 Male cable and no power cable connected to boot the ASIAIR into Loader mode.
> 1. First plug the USB-C end into the ASIAIR
> 2. Fold the Reset button down
> 3. No plug in the USB-A 2.0 Male cable to your linux computer


