---
title: CoreELEC 介绍
summary: 了解 CoreELEC 及其在紧急情况下的使用方法。
date: 2025-03-01
weight: 5
ShowToc: true
TocOpen: true
---

**CoreELEC 自动重启尚未实现**

如果您尝试播放 **DoVi P7 FEL** 并导致错误代码，或在特定电影上反复崩溃，您可能会被重定向到此页面。

DoVi P7 FEL
: Dolby Vision Profile 7 Full Enhancement Layer

> show image comparison of 1 Android error code 2 Windows just red screen 3 CoreELEC able to play

## Reboot to CoreELEC
To perform the reboot manually, follow the steps below
1. Insert the USB drive with CoreELEC installed (see image below)
2. Exit the current application
3. Locate the app `Reboot to CoreELEC` and follow the instructions (see image below)

> [!note] [Reboot Automatically](../../../../reboot2ce)
> If the link above doesn't work, try [this](../../../../../reboot2ce)
>
> If neither links work or returns `internal server error`, it's likely not implemented yet.

> image for manual reboot
## Using CoreELEC
CoreELEC is based on Kodi, it will be play to playback any files that are not supported on Android. First, login to the correct account. Since the automatic reboot is not implemented yet, you will need to find the movie that you are having problem with manually.

> [!error] Android TV Remote does not work
> In CoreELEC, the Android TV remote will not work, you'll need to use the Samsung TV Remote or the Logitech K400 keyboard (connect it via USB) to navigate the system. See [here](../remote) for all the remotes.

## Alternative: Use a laptop
> [!warning] Windows and Dolby Vision
> In Windows, Dolby Vision is not supported, and any DoVi files regardless of P7 FEL or not will be displayed as regular HDR. Additionally, HDR10+ is not also not supported. These files are best played on CoreELEC. However, if you are unable to use CoreELEC or prefer the versatility of Windows, you can use a laptop to play the files.

Will be implemented later.