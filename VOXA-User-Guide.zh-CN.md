# VOXA 安装与使用教程

[English](./VOXA-User-Guide.md) · **简体中文**

VOXA 可以把 Apple TV Siri Remote 用作 Mac 的遥控输入设备，支持按键映射、触控操作、快捷指令和场景切换。

麦克风版（付费功能）可将支持的 Apple TV Siri Remote 内置麦克风直接作为 Mac 的麦克风使用。

## 系统要求

- Apple Silicon Mac（M1、M2、M3、M4 或更新型号）
- macOS 13 Ventura 或更高版本
- Apple TV Siri Remote 已通过蓝牙与 Mac 配对

> 当前安装包为 arm64，仅支持 Apple Silicon，不支持 Intel Mac。

## 安装

1. 从 [Releases](https://github.com/jinzongma/apple-tv-remote-for-mac/releases/latest) 下载 `VOXA-2.0.1-Build93.dmg`。
2. 双击打开 DMG。
3. 将 `Voxa.app` 拖入右侧的“应用程序”文件夹。
4. 在 Finder 中打开“应用程序”，然后双击 `Voxa.app`。

## 第一次使用

1. 打开 VOXA。
2. 按照提示授予“辅助功能”和“输入监控”权限；修改权限后，建议完全退出并重新打开 VOXA。
3. 在 macOS“系统设置 → 蓝牙”中确认 Siri Remote 已连接。
4. 在 VOXA 的“映射”页面中选择遥控器按键并设置对应操作。
5. 如需按 App 使用不同映射，请在“场景”页面添加应用并启用自动切换。

## 更新旧版本

1. 退出正在运行的 VOXA。
2. 打开新版 DMG。
3. 将新版 `Voxa.app` 拖入“应用程序”，选择“替换”。
4. 重新打开 VOXA；通常会保留现有按键映射和设置。

## 常见问题

### 按键映射没有反应

检查“辅助功能”和“输入监控”权限是否已开启，然后完全退出并重新打开 VOXA。请勿同时保留多个同版本 VOXA 副本。

### 找不到 Siri Remote

先在 macOS“系统设置 → 蓝牙”中确认遥控器已经完成配对并显示为已连接，再回到 VOXA 重新连接。

## 版本信息

- 当前版本：**VOXA 2.0.1（Build 93）**
- 安装包：Developer ID 签名并通过 Apple 公证
- SHA-256：`aea8c6a39604fefa6bf5e55bd54bdcdc1d5da42ebab21ac33914da1e98e74240`

## 联系方式

如有问题或建议，请发送邮件至 [huabeijinzongma@icloud.com](mailto:huabeijinzongma@icloud.com)。
