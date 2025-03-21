---
title: "Network Buffering"
summary: How to network buffering issues on your during media playback.
date: 2025-03-01
weight: 5
ShowToc: true
TocOpen: true
---

You are likely redirected here because you selected network buffering as the issue you are experiencing. Due to the closed source nature of Android TV, the troubleshooter is not able to diagnose or fix the issue. Follow the steps below to fix the issue.

## Local Playback
Since the playback will always occur over the LAN for now, buffering due to lack of bandwidth is very unlikely to occur. You may have been mistaken the cause of the issue. 
### Long Time to Load Media in the Beginning
Some movies are stored on the archival HDD which is kept spun down most of the time to save power. The HDD will need to spin up before the movie can be played. This type of buffering normal behavior and not a network issue.
### Audio Stutter, Video Freeze
For some media files, specifically DTS-HD MA audio, it's likely you'll experience audio or video freezing or stuttering. This is due to the Problematics Box R 4K Plus in Android and it's impossible to fix, there is nothing wrong with the network bandwidth. If this is bothering you, you can try to play the media using [CoreELEC](/posts/tvbox/coreelec) for a flawless playback experience.

## Remote Playback
This is reserved for future use. In case when the server is moved to another location and the playback is done remotely, buffering may occur due to the lack of bandwidth. However, due to the closed source nature of Android TV, the troubleshooter is not able to diagnose or fix the issue. But you can try to diagnose manually.

Since the troubleshooter runs on the same machine as the Jellyfin server, it will be able to perform some basic checks to see if the server is reachable from the internet and the network bandwidth is sufficient. Run the tests below to diagnose the issue.

> [!note] [Debug Internet Connection on Server](http://backend-server/not-implented)
> NOT IMPLEMENTED YET
