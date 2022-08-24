---
layout: post
title: Ubuntu22.04 LTS 安装
category: 编程学习
keywords: Ubuntu
---
安装Ubuntu需要注意的事项如下：

安装时选择Something else，然后将硬盘合理分为4个区:

逻辑分区(efi):500MB-1G

逻辑分区(swap):10-12G

主分区(ext4,根文件夹/):100G

主分区(ext4,用户文件夹/home):1T

注意，系统可能会自动分配efi分区，请务必手动重新分，不然会报错:sdb设备的一个vfat文件系统挂载到/boot/efi上失败;

此外，安装过程要断网以节省更新所需的时间。
