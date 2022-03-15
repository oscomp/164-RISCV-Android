# RISCV-Android
基于RISC-V架构平台的Android系统移植


## 项目描述

本项目的目标是实现android系统可以在RISC-V平台运行，需要移植AOSP的内核以及android软件系统。同时需要确保wifi、蓝牙、摄像头等硬件可以正常工作。
AOSP：Android操作系统的开源代码项目成立了AOSP（Android Open Source Project）  

Android:10或以上  
RISC-V平台：可选择starfive，HiFive Unmatched等riscv平台  
https://www.starfivetech.com/  
https://www.sifive.com/boards/hifive-unmatched  
项目可以基于源码：https://mirrors.tuna.tsinghua.edu.cn/help/AOSP/  
RISC-V：（发音为“risk-five”）是一个基于精简指令集（RISC）原则的开源指令集架构（ISA）。与大多数指令集相比，RISC-V指令集可以自由地用于任何目的，允许任何人设计、制造和销售RISC-V芯片和软件。虽然这不是第一个开源指令集，但它具有重要意义，因为其设计使其适用于现代计算设备（如仓库规模云计算机、高端移动电话和微小嵌入式系统）。设计者考虑到了这些用途中的性能与功率效率。

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

高

## 特征
 - 使用 RISC-V架构平台
 - 了解u-boot以及内核的构建
 - 了解android系统移植
 - 学习android系统开机启动具体流程

## License
任意开源license都可

## 预期目标
 - 满足安卓系统能够运行基本的软件（如：通讯录，闹铃，浏览器等）
 - 确保系统可以流畅运行主流软件，基本硬件等可以正常工作。
 - 可对系统做一定裁剪（比如移除google等服务等，根据磁盘容量去掉不需要的功能模块），确保系统精简，稳定。
 - 选择本项目的同学也可提出自己的新想法，得到导师认可支持后亦可加入预期目标或进阶特性
