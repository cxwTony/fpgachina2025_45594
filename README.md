# 基于3DGS的实时SLAM系统
使用Vitis HLS实现的改版3DGS，并基于AMD ZCU104和PYNQ实现完整的SLAM功能。\
本项目需要在zcu104上安装官方pynq镜像，具体参考官方教程，官方系统镜像下载链接：https://download.amd.com/opendownload/pynq/zcu104_v3.1.1.zip \

# 重要代码文件夹说明
platform中存储的是基础Vivado平台；\
overlay中存储的是Vitis HLS代码及配置文件；\
RapidReplication中包含链接完成的.bit和.hwh文件，推荐直接使用（放在~/pynq/overlays/my_project中）；\
pynq中为项目运行代码，直接导入进jupyter notebook中使用；

# 具体流程参考该仓库中的pynq/iphone_demo.ipynb
