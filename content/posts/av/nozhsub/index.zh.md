---
title: "为 Jellyfin 添加中文字幕"
summary: 如何为 Jellyfin 添加中文字幕。
date: 2025-03-01
weight: 3
ShowToc: true
TocOpen: true
---

如果您尝试在电影中使用故障排除工具但已经有中文字幕，可能会被要求访问此文档页面。这可能是因为视频播放器中未启用字幕。本页面将指导您如何在 Jellyfin 中启用中文字幕。

## 字幕格式
在本说明中，中文字幕将以以下形式出现：

### 内嵌字幕
这些字幕已经嵌入到视频文件中。常见的格式包括：
- SubRip (.srt)
- Advanced SubStation Alpha 
- 图形字幕格式 (.PGS)

一些视频已经包含中文字幕，并会显示为 `Chinese (Simplified)`。这些字幕通常只有一种语言。

### 外部字幕
这些字幕是作为独立文件提供的，与视频分开。这些字幕需要手动下载。在大多数最新电影中，提供以下两种类型的中文字幕：
- 多语言 (mul) - 中英文字幕
- 简体中文 (chi) - 中文字幕

要启用已存在的字幕，请按照以下步骤操作：

## Just Player
Just Player 是 Android 上的默认播放器，因其兼容性和较少的崩溃而被选用。要启用字幕，请按照以下步骤操作：
- 按下 [遥控器](../../tvbox/remote.md) 的 `Center` 键（稍后需要将其变为链接）以调出播放控制。
- 向下按两次。
- 按 `Right` 直到看到 `Subtitles` 图标。
- 在下拉菜单中选择所需的字幕。

按照教程更改字幕：
{{< rawhtml >}} 

<video width=100% controls>
    <source src="/support/images/zhsub.mp4">
    您的浏览器不支持 video 标签。  
</video>

{{< /rawhtml >}}

## Jellyfin 内置播放器
稍后完成。

## 报告问题
如果您无法看到字幕、添加字幕或认为 HTPC 故障排除工具存在错误，请使用以下表单联系我们（尚未实现）。

> [!note] [报告字幕问题](https://test.test)
> 在此报告字幕问题。
