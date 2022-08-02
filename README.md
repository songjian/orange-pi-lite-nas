# 使用Orange Pi Lite（香橙派Lite）开发板搭建NAS

![orangepi-lite-nas](https://i0.hdslb.com/bfs/archive/cbb2694561238a52f81fb6a4ef4d17c993d0637c.jpg@640w_480h)

[哔哩哔哩地址](https://www.bilibili.com/video/BV1FE411774H)

## 硬件&软件

### 硬件

* Orange Pi Lite 开发板 [官网介绍页](http://www.orangepi.cn/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-Lite.html)
* 西数1T 2.5寸移动硬盘
* 自组的500G移动硬盘

### 软件

* 操作系统：Armbian，[Armbian官网](https://www.armbian.com/orange-pi-lite/)
* nas软件：openmediavault

## 安装说明

### 操作系统烧入tf卡

1. 下载适合你开发板的img文件：[https://www.armbian.com/download/](https://www.armbian.com/download/)
2. 使用img文件制作系统tf卡，参考：[https://docs.armbian.com/User-Guide_Getting-Started/](https://docs.armbian.com/User-Guide_Getting-Started/)
3. 系统tf卡插入开发板，登录的帮助文档：[https://docs.armbian.com/User-Guide_Getting-Started/#how-to-login](https://docs.armbian.com/User-Guide_Getting-Started/#how-to-login)

### 安装openmediavault

1. 安装openmediavault
```sh
sudo apt update || sudo apt install openmediavault
```