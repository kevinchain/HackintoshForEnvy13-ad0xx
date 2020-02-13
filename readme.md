*注意！作者电脑型号为HP Envy-13 ad024TU，其中部分文件不建议大家直接用于其他型号的电脑。若使用本仓库中文件导致系统故障或崩溃，作者本人概不负责。

## ***欢迎！***

建立本仓库主要用于以下几个目的：

- 整理、分享适用于HP Envy-13 ad024TU的关于黑苹果的各种文件（驱动，补丁等）
- 总结个人折腾黑苹果的经验
- 与同好交流，提升自身水平，将黑苹果变得更加完美

希望大家都能够拥有一台自己心目中完美的黑苹果！**生命不息，折腾不止！**

**声明：仓库中所有文件均可供个人用途和技术交流使用，在转载时请务必标明出处。不得将此仓库中的任何文件用于任何商业活动！**

## ***请先了解以下内容***

- 作者电脑的网卡和硬盘均作了更换。故即使机型相同，直接套用此EFI依旧可能会产生问题，请知照！
- 此EFI一开始是来自于交流群中来源不明的envy-13通用EFI，里面的内容杂乱无章而且有很多不必要的驱动和补丁，但还是可以将机器驱动起来。经过大半年的维护，我对其中的内容作了一些精简，但是其中的方法依旧相对落后和杂乱。现在的这个EFI基本上是基于[SlientSliver](https://github.com/SilentSliver)的[HP-ENVY13-ad1XX-Hackintosh](https://github.com/SilentSliver/HP-ENVY-13-ad1XX-Hackintosh)修改而来，保留了其中的hotpatch部分，更改了一些驱动和补丁。特此鸣谢！
- 关于本机的功能：
  - CPU：可以正常变频
  - 电源：节能五项似乎没有完全加载，但是电池电量显示正常，使用上没有障碍
  - 显卡：仿冒的HD520，ig-platform-id为0x19160000，驱动原生显卡HD620会产生非常诡异的色阶断层
  - 睡眠：正常，以前曾有过睡眠唤醒掉蓝牙的问题，现在已经解决
  - 声音：使用的LayoutID为03，只能驱动底面的扬声器
  - 网卡：原配网卡无法使用，我更换为DW1560，没有故障出现
  - 触控板：正常，除了四指手势之外其他都可以用
  - 亮度调节：可调，但是档位间隔不大，最低档位的时候屏幕还是较亮
  - USB接口：四个接口均可正常使用
  - 摄像头：可用
  - 读卡器：无法驱动



附：作者电脑配置

| 型号 | HP Envy-13 ad024TU                                 |
| ---- | -------------------------------------------------- |
| CPU  | Intel Core i7-7500U(2.7GHz)                        |
| RAM  | 8GB DDR4                                           |
| 显卡 | Intel HD-620                                       |
| 硬盘 | ~~Intel SSDPEKKF360G7H 360G~~ （已更换为WD SN500） |
| 网卡 | ~~Intel 7265NGW~~（已更换为BCM94352Z）             |
| 声卡 | ALC295                                             |



致谢：

[RehabMan](https://github.com/RehabMan)

[黑果小兵](https://blog.daliansky.net)

[SlientSliver](https://github.com/SilentSliver)

[IT密码](https://www.itpwd.com)

[darkhandz](https://github.com/darkhandz)

以及其他给予过我帮助的网友们😘

