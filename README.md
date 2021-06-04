# Colorful-B460i-Hackintosh
## EFI 
OpenCore: 0.6.9

macOS version: BigSur 11.4

## 功能测试
- [x] 睡眠/唤醒
- [x] 所有USB端口
- [x] 核显硬件加速
- [x] 独显免驱支持
- [x] WiFi
- [ ] 蓝牙(暂未确定是EFI 问题还是我硬件问题)
- [x] 有线网卡正常
- [x] 显示器 DP 输出

## 硬件配置
| 规格     | 详细信息                                     |
| -------- | ---------------------------------------- |
| 主板型号 | 七彩虹  CVN B460I GAMING V20 |
| 处理器 | 英特尔 酷睿 i3-10100 处理器 |
| 独立显卡 | 盈通 RX 550 4G D5 极速版 |
| 内存 | 16GB 英睿达 DDR4 3200MHz |
| 硬盘 | 海康威视 C2000PRO 512G |
| 集成显卡 | 英特尔 核显 UHD630 |
| 显示器 | AOC  U2790PC 4k 27寸 |
| 无线网卡 | 英特尔 Wireless-AX200|

## BIOS 设置

参考：https://post.smzdm.com/p/awx4d25m/

## 系统截图

下次提交上传

## 注意事项

1. 序列号需使用 [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) 生成三码，分别填入config.plist中的MLB(Board Serial Number)，SystemSerialNumber，SystemUUID中， [教程](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html)

## 其他链接

[OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

[OpenCorePKG](https://github.com/acidanthera/OpenCorePkg)

[ProperTree](https://github.com/corpnewt/ProperTree)
