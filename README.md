# Hackintosh-Monterey-MacOS-OC0.7.6-EFI-for-10900es-b560m-RX580

机器配置：
CPU：intel十代10900es   
主板：华硕b560m-k（网卡intel I219-V）  
显卡：Radeon RX580 4G   
wifi/蓝牙卡：苹果Bcm94260cs2转接pcie卡   

说明：2022-01-29  
1、基于苹果小兵monterey12.1 OS的底包，提取config_RocketLake.plist制作，主要适配华硕b560m的主板；   
    - 定制iMac20.1的sn/UUID等信息     
    - 用usbtoolbox做了usb3.0/2.0端口定制，加载生成的usbtoolbox.kext及utbmap.kext，保证usb口正确辨识和工作       
    - 勾选DisableRtcChecksum，防止重启后bios安全自检失败  
2、Radeon独显输出，intel核显解码正常；     
4、目前运行完美，无线、蓝牙、休眠工作正常；   
5、AirDrop正常。  
 

<img width="715" alt="截屏2022-01-18 12 24 02" src="https://user-images.githubusercontent.com/97930740/149871347-a362b2a0-9851-43de-89ec-b0d230a0881f.png">
