# i5-10400F_TUF-GAMING-B460M-PLUS. 
- OpenCore 更新至 0.8.2  (2022-07-18)
- OpenCore 更新至 0.8.1  (2022-06-21)
- OpenCore 更新至 0.7.9  (2022-03-9)
- OpenCore 更新至 0.7.8  (2022-02-14)
## 已知问题  
- ~usb3.0无法驱动~
- ~RTC 写入错误 [解决方法](https://dortania.github.io/OpenCore-Post-Install/misc/rtc.html)~
## 机器配置
- OS：Monterey
- CPU: i5 10400F  
- 主板: ASUS TUF-GAMING-B460M-PLUS  
- 显卡: AMD RX580  
- WIFI: intel 9260AC
## 注意事项
- CFG LOCK 已解锁，如果Bios没有解锁请修改config.plist相关配置
- 使用时需在config中更改自己生成的机型信息
- 独显硬解需要将机型改为MacPro7,1
- 蓝牙驱动针对Monterey有效
