# RaspberryPi-CM4-ROS2-Camera-Guide

# （可选）更改启动顺序
# 1. 烧录启动盘
若希望从nvme启动，则一定要选择21.10版本的Ubuntu，否则在启动会报start4.elf版本不够新的问题。
我这里选择了Ubuntu Server，因为最后做出来的软件是服务器模式，不需要界面
# 2. 进行boot初始配置
配置gpu_mem,usb,cam等基本项
# 2. 启动系统，进行系统初始配置
# 3. 安装OpenCV测试
# 4. 发现问题
当前没有同时支持NVME启动，ROS2与双摄像头的系统，
Ubuntu 21.10与Manjaro可以支持双摄像头且可以从NVME启动，但是没办法支持ROS2，
Ubuntu 20.04 Desktop与Server可以支持双摄像头与ROS2，但是没办法完美的从NVME启动。
手动狗头
