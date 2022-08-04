---
title: GetInputPropertiesListPropertyItems
description: OBS Studio Requests Reference (v5)
published: true
date: 2022-08-04T05:38:06.382Z
tags: 
editor: markdown
dateCreated: 2022-08-04T05:38:06.382Z
---

## Overview
Gets the items of a list property from an input's properties.

Note: Use this in cases where an input provides a dynamic, selectable list of items. For example, display capture, where it provides a list of available displays.

## Request Fields
Name | Type | Required| Description |
----:|:----:|:-------:|:------------|
`inputName` | `String`{.datatype} | <i class="mdi mdi-check-bold"></i> | Name of the input
`propertyName` | `String`{.datatype} | <i class="mdi mdi-check-bold"></i> | Name of the list property to get the items of

## Variables
Name | Type | Description | 
----:|:---------:|:------------|
`obsRaw.propertyItems` | `Array<Object>`{.datatype} | Array of items in the list property

## Data Fields
:---|:---:|
Complexity Rating: | <span class="stars stars--4"></span>
Latest Supported RPC Version: | *1*{.obs-version-badge}
Added in | *v5.0.0*{.obs-version-badge}

## Copy/Paste
```json
{
  "request-type": "GetInputPropertiesListPropertyItems",
  "inputName": "",
  "propertyName": ""
}
```

---

- [<i class="mdi mdi-chevron-left"></i>**OBS Studio Requests Reference *Go Back***](/en/Broadcasters/OBS/Requests)
- [<i class="mdi mdi-github"></i> **OBS WebSocket Documentation *GitHub documentation for this request***](https://github.com/obsproject/obs-websocket/blob/master/docs/generated/protocol.md#getinputpropertieslistpropertyitems)
{.btn-grid .my-5}