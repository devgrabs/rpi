# Raspberry pi3 Qt5 installer

## Pre install
### Raspbian 2017-07-05-raspbian-jessie on Raspberry 3 model B

    sudo apt-get build-dep qt4-x11
    sudo apt-get install qt5-default qtbase5-dev qtdeclarative5-dev qt5-qmake qtcreator libqt5gui5
    sudo apt-get install qtscript5-dev qtmultimedia5-dev libqt5multimedia5-plugins qtquickcontrols2-5-dev
    sudo apt-get install libqt5network5 cmake build-essential
    sudo apt-get install libudev-dev libinput-dev libts-dev libxcb-xinerama0-dev libxcb-xinerama0

#### Host PC (ubuntu 18.04)
Edit sources list in /etc/apt/sources.list with use of your favorite editor (nano / vi) and uncomment the deb-src line:

    sudo apt-get install sshpass
    sshpass -p raspberry ssh pi@10.0.0.221(raspberrypi ip)
