# broadcom-sta
Working copy of broadcom 4315 wifi driver on centos 7.5

### Steps to run
```shell
yum install gcc automake git -y
git clone https://github.com/rohitggarg/broadcom-sta
cd broadcom-sta
make
sudo make install
sudo depmod -a
sudo modprobe wl
```
