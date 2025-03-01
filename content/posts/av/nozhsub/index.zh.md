---
title: "Adding Chinese Subtitles to Jellyfin"
summary: How to add Chinese subtitles to Jellyfin.
date: 2025-03-01
weight: 3
ShowToc: true
TocOpen: true
---

You may be asked to visit this documentation page if you tried to use the troubleshooter on a movie that already have Chinese subtitles. It is likely the subtitle is not enabled in the video player. This page will guide you through the process of enabling Chinese subtitles in Jellyfin.
## Subtitle Formats
For the purpose of documentation, the Chinese subtitles will come in the following forms
### Internal Subtitles
These are subtitles that are already embedded in the video file. There are several formats such as
- SubRip (.srt)
- Advanced SubStation Alpha 
- Graphic Subtitle Format (.PGS)
######
Some of the videos already have Chinese subtitles, and it will be displayed as `Chinese (Simplified)`. These subtitles usually have only one language.
### External Subtitles
These are subtitles that are provided as separate files from the video. These are downloaded manually. In most up to date movies, 2 types of Chinese subtitles are provided
- Multiple languages (mul) - 中英文字幕
- Simplified Chinese (chi) - 中文字幕

To enable the subtitles that are already present, follow the steps below
## Just Player
Just Player is the default player on Android due to its compatibility and lesser crashes. To enable the subtitles, follow the steps below
- Press `Center` on the [remote](../../tvbox/remote.md) (need to make into a link later) to bring up the playback controls
- Press `Down` twice
- Press `Right` until you see `Subtitles` icon
- Under the dropdown, choose the desired subtitles

> Add image here
## Jellyfin Internal Player
Todo later.
## Report Issues
If you are unable to see the subtitles, add subtitles or believe the HTPC troubleshooter has made an mistake, please contact using the form below (not implemented yet)

> [!note] [Report Subtitle Issue](https://test.test)
> Report subtitle issues here.

