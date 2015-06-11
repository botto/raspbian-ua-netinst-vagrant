# raspbian-ua-netinst-vagrant
Simple vagrant machine to create a raspbery pi ua installer

A vagrant machine that will allow you to run
https://github.com/debian-pi/raspbian-ua-netinst
without having to install deps


Simply
```
git clone https://github.com/botto/raspbian-ua-netinst-vagrant.git
cd raspbian-ua-netinst-vagrant
vagrant up
vagrant ssh
cd rpi-ua-inst
./update.sh
./build.sh
sudo ./buildroot.sh
```
Now you have a img file to burn to your sd card
