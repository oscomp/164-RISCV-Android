# RISCV-Android
基于RISC-V架构平台的Android系统移植


## 项目描述

本项目的目标是实现android（10 or above）系统可以在RISC-V平台运行，需要移植AOSP（Android Open Source Project）的内核以及android软件系统。同时需要确保wifi、蓝牙、摄像头等硬件可以正常工作。

## 所属赛道

2022全国大学生操作系统比赛的“OS功能挑战”赛道

## 参赛要求

 - 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生（2022年春季学期或之后毕业的本科生及研究生）
 - 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖 请遵循“2022全国大学生操作系统
 - 比赛”的章程和技术方案要求

## 项目导师
 - 林博: linbo@kylinos.cn
 - 张志成: zhangzhicheng@kylinos.cn

## 难度

   高等

## 特征
 - 使用 RISC-V架构平台
 - 了解u-boot以及内核的构建
 - 了解android系统移植
 - 了解android系统开机启动流程
 - 
## 参考文档
项目可以基于源码：https://mirrors.tuna.tsinghua.edu.cn/help/AOSP/

## License
任意开源license都可

## 预期目标
 - 满足安卓系统能够运行基本的软件（如：通讯录，闹铃，浏览器等）
 - 确保系统可以流畅运行主流软件，基本硬件等可以正常工作。
 - 可对系统做一定裁剪（比如移除google等服务等，根据磁盘容量去掉不需要的功能模块），确保系统精简，稳定。
 - 满足android系统性能测试要求
 - 选择本项目的同学也可提出自己的新想法，得到导师认可支持后亦可加入预期目标或进阶特性

## 说明
RISC-V平台可选择starfive，HiFive Unmatched等riscv平台，参考链接：
https://www.starfivetech.com/
https://www.sifive.com/boards/hifive-unmatched
