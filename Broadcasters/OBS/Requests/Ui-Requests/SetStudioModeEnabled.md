---
title: SetStudioModeEnabled
description: OBS Studio Requests Reference (v5)
published: true
date: 2022-08-06T18:04:23.395Z
tags: 
editor: markdown
dateCreated: 2022-08-06T18:04:23.395Z
---

## Overview
Enables or disables studio mode

## Request Fields
Name | Type | Required| Description |
----:|:----:|:-------:|:------------|
`studioModeEnabled` | `Boolean`{.datatype} | <i class="mdi mdi-check-bold"></i> | True == Enabled, False == Disabled

## Data Fields
:---|:---:|
Complexity Rating: | <span class="stars stars--1"></span>
Latest Supported RPC Version: | *1*{.obs-version-badge}
Added in | *v5.0.0*{.obs-version-badge}

## Usage
## Tabset {.tabset}
### OBS raw
```json
{
  "request-type": "SetStudioModeEnabled",
  "studioModeEnabled": 
}
```
## End Tabset {.tabset}

---

- [<i class="mdi mdi-chevron-left"></i>**OBS Studio Requests Reference *Go Back***](/en/Broadcasters/OBS/Requests)
- [<i class="mdi mdi-github"></i> **OBS WebSocket Documentation *GitHub documentation for this request***](https://github.com/obsproject/obs-websocket/blob/master/docs/generated/protocol.md#setstudiomodeenabled)
{.btn-grid .my-5}