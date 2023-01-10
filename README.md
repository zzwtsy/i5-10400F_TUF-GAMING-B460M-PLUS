# i5-10400F_TUF-GAMING-B460M-PLUS.

# $\color{red}{注意事项}$

- CFG LOCK 已解锁，如果 Bios 没有解锁请修改 config.plist 相关配置
- $\color{red}{使用时需在 config 中更改自己生成的三码}$
- 独显硬解需要将机型改为 MacPro7,1
- 蓝牙驱动针对 Monterey 有效

## 已知问题

- ~~usb3.0 无法驱动~~
- ~~RTC 写入错误 [解决方法](https://dortania.github.io/OpenCore-Post-Install/misc/rtc.html)~~
- 睡眠唤醒

  修复方法
  <details>

  - [黑苹果睡了就醒？睡了自动醒？黑苹果睡眠问题的解决](https://www.bilibili.com/video/BV1B34y127Cf)

  - DarkWake 唤醒 （[来源](https://www.logcg.com/archives/3528.html)）

    <details>

        - 终端查看是否有 DarkWake 唤醒

          ```bash
          $ pmset -g log | grep DarkWake
          ```

        - 检查 powernap 是否为 0

          ```bash
          $ pmset -g
          ```

        - 关闭 PowerNap

          ```bash
          $ sudo pmset -a powernap 0
          ```

    </details>

  </details>

- 使用一段时间后系统变得非常卡顿 ~~(可能是我太穷了内存只有8G)~~

## 机器配置

- OS：Monterey
- CPU: i5 10400F
- 主板: ASUS TUF-GAMING-B460M-PLUS
- 显卡: AMD RX580
- WIFI: intel 9260AC

