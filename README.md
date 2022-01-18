# Hackintosh-EFI-for-10900es-b560m

机器配置：
CPU：intel十代10900es
主板：华硕b560m-k
显卡：Radeon RX580 4G
wifi/蓝牙卡：苹果Bcm94260cs2转接pcie卡

说明：2022-01-18
1、基于苹果小兵monterey12.1 OS的底包，提取config_RocketLake.plist制作，主要适配华硕b560m的主板；
2、用usbtoolbox做了usb3.0/2.0端口定制，解决了monterey蓝牙打不开问题；
3、目前运行完美，无线、蓝牙、休眠工作正常；

问题：
1、蓝牙与iphone连接后自动断开，原因不明。
