# NM-RF-HAT 

English | [简体中文](#简体中文)

**A Multi-functional RF Expansion Board for ESP32-2432S028 (Cheap Yellow Display, CYD)**

The NM-RF-HAT is a multi-functional Radio Frequency (RF) expansion board specifically designed for the ESP32-2432S028, commonly known as the "Cheap Yellow Display" or CYD. This repository aims to provide hardware design files, documents and related resources for the NM-RF-HAT, supporting developers and enthusiasts in RF experimentation and project development.

## Project Overview

The primary goal of the NM-RF-HAT is to simplify the process of RF project development and experimentation by integrating multiple commonly used RF modules onto a single, compact PCB. It effectively addresses the challenges of complex wiring and potential pin conflicts often encountered in traditional development, offering an efficient and integrated hardware solution for various RF applications.

This expansion board is particularly well-suited for projects utilizing firmware such as [BruceDevices](https://github.com/BruceDevices/firmware) and [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder), significantly enhancing the functionality and ease of use of these open-source tools.

## Key Features

The NM-RF-HAT integrates a variety of popular RF modules, providing extensive wireless communication capabilities:

*   **Multi-Band RF Support:**
    *   **CC1101:** Sub-1 GHz transceiver for applications like remote control devices.
    *   **nRF24L01:** 2.4 GHz transceiver supporting custom protocols and wireless communication.
    *   **PN532:** NFC/RFID module for reading and writing near-field communication tags.
    *   **IR:** Infrared transmitter and receiver for infrared remote control applications.
    *   **RF433:** 433MHz ASK (Amplitude Shift Keying) transmitter/receiver module.
*   **Power Management:** On-board power management features to ensure stable power supply.
*   **GNSS Expansion Interface:** Provides an interface for connecting Global Navigation Satellite System (GNSS) modules, supporting positioning functions.
*   **TF Card Slot:** For data logging and storage, facilitating project data management.
*   **Designed for CYD:** Seamlessly integrates with the ESP32-2432S028 (CYD) via a simple cable connection.

## Getting Started

This section will provide detailed guidance on how to connect the NM-RF-HAT to your CYD and begin RF experimentation. Specific content will be updated upon the release of hardware design files.

## Hardware Resources

This section will include the schematics and other hardware design files for the NM-RF-HAT. Based on community discussions, the relevant schematics are expected to be released soon.

## Community & Support

*   **Reddit Communities:** Join discussions on the [r/esp32](https://www.reddit.com/r/esp32/) and [r/brucefw](https://www.reddit.com/r/brucefw/) subreddits to get the latest information and community support.
*   **Thingiverse:** Find 3D printable cases for the NM-RF-HAT and CYD combination, such as [this design](https://www.thingiverse.com/thing:7305463).

## Contributing

We highly welcome contributions to this project! Please feel free to submit Pull Requests, open Issues, or share your valuable ideas.

# 简体中文

**ESP32-2432S028 (CYD) 的多合一射频扩展板**

NM-RF-HAT 是专为 ESP32-2432S028 (俗称“CYD”) 设计的一款多功能射频 (RF) 扩展板。本仓库旨在提供 NM-RF-HAT 的硬件设计文件、使用文档和相关资源，以支持开发者和爱好者进行射频实验和项目开发。

## 项目概述

NM-RF-HAT 的核心目标是通过将多个常用射频模块集成到一块紧凑的 PCB 上，从而简化射频项目的开发和实验过程。它有效解决了传统开发中复杂的布线和潜在的引脚冲突问题，为各类射频应用提供了一个高效且集成的硬件解决方案。

该扩展板尤其适用于运行 [BruceDevices](https://github.com/BruceDevices/firmware) 和 [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder) 等固件的项目，极大地提升了这些开源工具的功能性和易用性。

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

本节将提供详细的指南，说明如何将 NM-RF-HAT 连接到您的 CYD，并开始进行射频实验。具体内容将在硬件设计文件发布后更新。

## 硬件资料

本节将包含 NM-RF-HAT 的原理图和其他硬件设计文件。根据社区讨论，相关原理图预计将很快发布 [1]。

## 社区与支持

*   **Reddit 社区：** 参与 [r/esp32](https://www.reddit.com/r/esp32/) 和 [r/brucefw](https://www.reddit.com/r/brucefw/) 子版块的讨论，获取最新信息和社区支持。
*   **Thingiverse：** 查找适用于 NM-RF-HAT 和 CYD 组合的 3D 打印外壳，例如 [此设计](https://www.thingiverse.com/thing:7305463)。

## 贡献

我们非常欢迎对本项目做出贡献！请随时提交 Pull Request、提出 Issue 或分享您的宝贵想法。
