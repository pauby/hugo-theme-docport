---
description: The video shortcode allows you to display a video on your page.
title: video
---

The `video` shortcode allow you to display a local or remote video on your page. This is different from the Hugo `youtube` shortcode that only displays a YouTube video. This shortcode will display a video from any URL.

{{%alert%}}**This is** an alert !{{%/alert%}}

## Usage

`video` can use the following named parameters :

* src
* type
* preload

## Basic examples

```text
    {{< video src="http://url_or_local_filesystem/files/video.mp4" type="video/mp4" preload="false" >}}
```
