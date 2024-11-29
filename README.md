# UINIO-Keyboard 多功能输入模组

[**UINIO-Keyboard**](https://gitee.com/uinika/UINIO-Keyboard) 是一款基于[**江苏沁恒 CH452**](https://www.wch.cn/products/CH452.html) 的 64 位键盘输入装置，采用两线制的 **I²C** 总线通信接口，并且外扩有[**日本阿尔卑斯阿尔派（ALPSALPINE）**](https://www.alpsalpine.com/) 的 3 枚 **EC11** 旋转编码器、以及 1 枚 **RKJXV** 模拟量碳膜摇杆，基本覆盖了嵌入式开发当中主流的实体输入方案。

![](./Images/PCB-3D-1.png)

![](./Images/PCB-3D-2.png)

## 设计概要

1. 同时板载有 **编码键盘**、**旋转编码器**、**模拟量摇杆** 三种常用的输入外设；
2. 添加了六枚 `3mm` 直径的机械孔，便于使用**铜柱**或者**螺丝**进行固定和安装；
3. 键盘按键使用 `3 × 4 × 2.5` 封装规格的四引脚贴片按键，这里可以购买日本[**阿尔卑斯阿尔派**](https://www.alpsalpine.com/c/)的 `SKRPACE010` 型，或者国产[**讯普精密**](https://www.xunpu.com.cn/)的 `TS-1089S-02526` 型微动按键；
4. 碳膜摇杆如果购买不到日本**阿尔卑斯阿尔派**（ALPS Alpine）的原厂型号，那么可以平替为国产的 [**广东控银 JP13**](http://www.k-silver.com/c_html_products/jp13heisedaikaiguan-825.html) 型摇杆；
5. 关于 64 位键盘的具体键位编码，以及参考驱动程序，可以查阅沁恒官方的[**《数码管驱动及键盘控制芯片 CH452 数据手册》**](https://www.wch.cn/downloads/CH452DS1_PDF.html)；

## 参考技术文档

[UinIO.com 电子技术实验室](http://uinio.com/) 为 **UINIO-Keyboard** 开源项目提供了如下参考技术资料：

- [**《BOM 交互式物料清单与 PCB 布线在线预览》**](http://uinio.com/archives/BOM/UINIO-Keyboard.html)
- [《UINIO-Keyboard 核心板原理图》](http://uinio.com/my/works/UINIO-Keyboard/UINIO-Keyboard-Schematic.pdf)
- [《交互式 BOM 物料清单与 PCB 版图在线预览》](http://uinio.com/my/works/UINIO-Keyboard/UINIO-Keyboard-BOM.html)