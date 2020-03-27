# Acer-E5-572G-528R-Hackintosh

宏基E5-572G-528R 黑苹果驱动



## 适配系统

**Catalina 10.15.3**

## 硬件配置

| 规格     | 详细信息                                     |
| -------- | -------------------------------------------- |
| 电脑型号 | 宏基E5-572G-528R                             |
| 处理器   | 英特尔 酷睿 i5-4210M                         |
| 硬盘     | SanDisk SATA 240G SSD + Seagate 2T           |
| 显卡     | Intel HD Graphics 4600 / Nvidia GeForce 840M |
| 内存     | 16 GB LPDDR3                                 |
| 显示器   | 15.6 英寸 FHD 1920x1080                      |
| 声卡     | Realtek ALC283                               |
| 有线网卡 | Realtek RTL8168                              |
| 无线网卡 | 更换 miniPCI-e  博通BCM94360HMB              |



## 驱动情况

- [x] 核显正常，独显屏蔽
- [x] 有线网卡正常
- [x] 无线网卡更换博通，免驱
- [x] 双屏输出正常。本机屏幕+HDMI输出，VGA无法使用
- [x] USB驱动正常
- [x] 声音输出正常，可以使用自带Fn+键盘左右键调节
- [x] 亮度调节正常，使用Fn+F2和Fn+Pause Break调节
- [ ] 睡眠唤醒异常，唤醒会重启，在节能中关闭休眠



## 说明

得到更好的显示效果，安装完成后自行开启HIDPI，使用如下一键脚本

https://github.com/xzhih/one-key-hidpi
