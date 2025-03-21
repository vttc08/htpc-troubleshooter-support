---
title: CoreELEC 介绍
summary: 了解 CoreELEC 及其在紧急情况下的使用方法。
date: 2025-03-01
weight: 5
ShowToc: true
TocOpen: true
---

**CoreELEC 自动重启功能尚未实现**

如果您尝试播放 **DoVi P7 FEL** 导致错误代码，或者在播放某部电影时反复崩溃，您可能会被重定向到此页面。

DoVi P7 FEL
: Dolby Vision Profile 7 Full Enhancement Layer（杜比视界第七代全增强层）

![p7fe](/support/images/p7fel.jpg)

## 重启到 CoreELEC
要手动执行重启，请按照以下步骤操作：
1. 插入安装了 CoreELEC 的 USB 驱动器（见下图）
2. 退出当前应用程序
3. 找到应用程序 `Reboot to CoreELEC` 并按照说明操作（见下图）

> [!note] [自动重启](../../../../../reboot2ce)
> 如果以上链接无效，请尝试 [此链接](../../../../reboot2ce)
>
> 如果两个链接都无效或返回 `internal server error`，则可能尚未实现。

### 手动重启
![CoreELEC USB 驱动器](/support/images/ceusb.jpg)
{{< rawhtml >}}
<video width=100% controls>
    <source src="/support/images/cereboot.mp4">
    您的浏览器不支持视频标签。
{{< /rawhtml >}}

## 使用 CoreELEC
CoreELEC 基于 Kodi，可以播放 Android 不支持的任何文件。首先，登录正确的账户。由于自动重启功能尚未实现，您需要手动找到您遇到问题的电影。

> [!error] Android TV 遥控器无法使用
> 在 CoreELEC 中，Android TV 遥控器无法使用，您需要使用三星电视遥控器或 Logitech K400 键盘（通过 USB 连接）来操作系统。有关所有遥控器的信息，请参见 [此处](../remote)。

## 替代方案：使用笔记本电脑
> [!warning] Windows 和杜比视界
> 在 Windows 中，不支持杜比视界，任何 DoVi 文件无论是否为 P7 FEL 都会显示为普通 HDR。此外，HDR10+ 也不支持。这些文件最好在 CoreELEC 上播放。然而，如果您无法使用 CoreELEC 或更喜欢 Windows 的多功能性，可以使用笔记本电脑播放这些文件。

稍后将实现。