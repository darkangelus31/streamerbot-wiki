---
title: MediaInputActionTriggered
description: OBS Studio Events Reference (v5)
published: true
date: 2022-08-08T18:25:41.824Z
tags: 
editor: markdown
dateCreated: 2022-08-08T18:25:41.824Z
---

## Overview
An action has been performed on an input.

## Variables
Name | Type | Description | 
----:|:----:|:------------|
`obsEvent.inputName` | `String`{.datatype} | Name of the input
`obsEvent.mediaAction` | `String`{.datatype} | Action performed on the input. See `ObsMediaInputAction` enum

## Data Fields
:---|:---:|
| Complexity Rating: | <span class="stars stars--2"></span>
| Latest Supported RPC Version: | *1*{.obs-version-badge}
| Added in | *v5.0.0*{.obs-version-badge}

---

- [<i class="mdi mdi-chevron-left"></i>**OBS Studio Events Reference *Go Back***](/en/Broadcasters/OBS/Events)
- [<i class="mdi mdi-github"></i> **OBS WebSocket Documentation *GitHub documentation for this request***](https://github.com/obsproject/obs-websocket/blob/master/docs/generated/protocol.md#mediainputactiontriggered)
{.btn-grid my-5}