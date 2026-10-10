# NM-RF-HAT 设备扩展板

[English](README.md) | 简体中文

**NM-RF-HAT：适用于 ESP32-2432S028 (Cheap Yellow Display, CYD) 和 NM-CYD-C5 的多合一射频扩展板**

NM-RF-HAT 是专为 ESP32-2432S028 (俗称“CYD”) 设计的一款多功能射频 (RF) 扩展板。本仓库旨在提供 NM-RF-HAT 的硬件设计文件、使用文档和相关资源，以支持开发者和爱好者进行射频实验和项目开发。

## 项目概述

NM-RF-HAT 的核心目标是通过将多个常用射频模块集成到一块紧凑的 PCB 上，从而简化射频项目的开发和实验过程。它有效解决了传统开发中复杂的布线和潜在的引脚冲突问题，为各类射频应用提供了一个高效且集成的硬件解决方案。

该扩展板尤其适用于运行 [BruceDevices](https://github.com/BruceDevices/firmware) 、[HaleHound-CYD](https://github.com/JesseCHale/HaleHound-CYD) 和 [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder) 等固件的项目，极大地提升了这些开源工具的功能性和易用性。

NM-RF-HAT 扩展板已支持 ESP32-2432S028 设备以及我们的 [NM-CYD-C5](https://github.com/RockBase-iot/NM-CYD-C5) 开发板。

![NM-RF-HAT 引脚图](Documentation/pics/NM-RF-HAT-pinout.png)

### RockBase 彩色版

RockBase 彩色版的 NM-RF-HAT 采用了独特的配色方案，便于识别不同的模块和连接。该版本保持了标准 NM-RF-HAT 的所有功能，同时为开发者和爱好者提供了更具视觉效果的体验。*注意：彩色版与标准版在功能与引脚上完全一致，仅在外观上有所不同。*

![RockBase 彩色版](Documentation/pics/rf-hat-color.png)

![RockBase 彩色版背景](Documentation/pics/rf-hat-color-bg.png)

## 主要特性

NM-RF-HAT 集成了多种流行的射频模块，提供广泛的无线通信能力：

*   **多频段射频支持：**
    *   **CC1101：** 用于 Sub-1 GHz 频段的收发器，适用于遥控设备等应用。
    *   **nRF24L01：** 2.4 GHz 频段收发器，支持自定义协议和无线通信。
    *   **PN532：** NFC/RFID 模块，用于读写近场通信标签。
    *   **IR：** 红外发射器和接收器，适用于红外遥控应用。
    *   **RF433：** 433MHz ASK (幅移键控) 发射/接收模块。
*   **电源管理：** 板载电源管理功能，支持电池充放电，确保稳定供电。
*   **GNSS 扩展接口：** 提供连接全球导航卫星系统 (GNSS) 模块的接口，支持定位功能。
*   **TF 卡槽：** 用于数据记录和存储，方便项目数据的管理。
*   **专为 CYD 设计：** 通过简单的线缆连接即可与 ESP32-2432S028 (CYD) 无缝配合。

## 快速入门

本节将提供详细的指南，说明如何将 NM-RF-HAT 连接到您的 CYD，并开始进行射频实验。具体内容将在硬件设计文件发布后更新，您可以从 `Documentation` 目录获取原理图和用户手册。

## 硬件资料

本节包含 NM-RF-HAT 的原理图和其他硬件设计文件，您可以在 `Documentation` 目录中找到原理图和用户手册。

## 常见问题与解答

如果在使用 NM-RF-HAT 时遇到问题，您可以先参考博客 [NM-RF-HAT FAQ - Common Questions & Answers](https://rockbase.shop/blogs/tech-news/nm-rf-hat-faq) 或 [NM-RF-HAT 常见问题](NM-RF-HAT%20FAQ.md)。

## 购买渠道

您可以通过 RockBase 的 Aliexpress 和 Shopify 商店购买 NM-RF-HAT。

- [RockBase IoT Store](https://www.aliexpress.com/store/1105401362)
- [RockBase Shop](https://rockbase.shop/products/nm-rf-hat)

### 配件提醒

设备电池接口为JST 1.25 PH 2-pin，红色为正，黑色为负，选择电池时，请确保正确连接以避免损坏设备。可根据实际需求选择合适的电池容量和类型，[速卖通购买](https://www.aliexpress.com/item/3256809292266438.html)。

![JST 1.25 PH 2-pin 接口示意图](Documentation/pics/jst_interface.png)


## 社区与支持

*   **Reddit 社区：** 参与 [r/esp32](https://www.reddit.com/r/esp32/) 和 [r/brucefw](https://www.reddit.com/r/brucefw/) 子版块的讨论，获取最新信息和社区支持。
*   **Thingiverse：** 查找适用于 NM-RF-HAT 和 CYD 组合的 3D 打印外壳，例如 [此设计](https://www.thingiverse.com/thing:7305463)。
*   **[HaleHound-CYD](https://github.com/JesseCHale/HaleHound-CYD)：** 该项目已支持 NM-RF-HAT 和 ESP32-2432S028。

## 贡献

我们非常欢迎对本项目做出贡献！请随时提交 Pull Request、提出 Issue 或分享您的宝贵想法。
