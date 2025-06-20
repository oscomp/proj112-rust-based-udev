# proj112-rust-based-udev
用rust语言重新设计与实现udev设备管理

用rust语言重新设计与实现udev设备管理

## 项目描述

udev 是一个为你的计算机提供设备事件的 Linux 子系统。udev 是一个非常灵活的系统，用户态udev通过接受硬件的uevent事件来匹配对应的规则，然后进行相应的处理。

当前使用比较广泛的是systemd-udevd，与systemd社区强绑定。可以使用rust语言设计与实现一个新的udev设备管理软件，保持独立性和兼容性，且兼具Rust语言的安全可靠能力。

## 所属赛道

2025全国大学生操作系统比赛的“OS功能设计”赛道

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师

- gitee @overweight
- email hexiaowen@huawei.com

## 难度

中等

## 特征

- 提供高效安全的event事件处理框架，支持规则匹配与worker调度
- 兼容现有的udev规则
- udev系统可以分为三个部分：
  - libudev函数库，可以用来获取设备的信息。
  - udevd守护进程，处于用户空间，用于管理虚拟`/dev`
  - 管理命令udevadm，用来诊断出错情况。

## 进阶特性

可与导师沟通，得到导师的认可与支持后加入。

## License

任意开源license都可

## 预期目标

特征中的要求为必备能力，进阶特性为建议内容，不要求一定完成。选择本项目的同学也可提出自己的新想法，得到导师认可支持后亦可加入预期目标或进阶特性。
