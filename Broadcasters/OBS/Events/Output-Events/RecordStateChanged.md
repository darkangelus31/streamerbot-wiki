---
title: RecordStateChanged
description: OBS Studio Events Reference (v5)
published: true
date: 2022-08-08T18:07:37.969Z
tags: 
editor: markdown
dateCreated: 2022-08-08T18:07:37.969Z
---

## Overview
The state of the record output has changed.

## Variables
Name | Type | Description | 
----:|:----:|:------------|
`obsEvent.outputActive` | `Boolean`{.datatype} | Whether the output is active
`obsEvent.outputState` | `String`{.datatype} | The specific state of the output
`obsEvent.outputPath` | `String`{.datatype} | File name for the saved recording, if record stopped. `null` otherwise

## Data Fields
:---|:---:|
| Complexity Rating: | <span class="stars stars--2"></span>
| Latest Supported RPC Version: | *1*{.obs-version-badge}
| Added in | *v5.0.0*{.obs-version-badge}

---

- [<i class="mdi mdi-chevron-left"></i>**OBS Studio Events Reference *Go Back***](/en/Broadcasters/OBS/Events)
- [<i class="mdi mdi-github"></i> **OBS WebSocket Documentation *GitHub documentation for this request***](https://github.com/obsproject/obs-websocket/blob/master/docs/generated/protocol.md#recordstatechanged)
{.btn-grid my-5}