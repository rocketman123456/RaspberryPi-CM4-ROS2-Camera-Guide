# RaspberryPi-CM4-ROS2-Camera-Guide

# （可选）更改启动顺序
# 1. 烧录启动盘
若希望从nvme启动，则一定要选择21.10版本的Ubuntu，否则在启动会报start4.elf版本不够新的问题。
我这里选择了Ubuntu Server，因为最后做出来的软件是服务器模式，不需要界面
# 2. 进行boot初始配置
配置gpu_mem,usb,cam等基本项
# 2. 启动系统，进行系统初始配置
# 3. 安装OpenCV测试
