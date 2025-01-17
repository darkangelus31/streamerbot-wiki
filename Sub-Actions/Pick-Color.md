---
title: Pick Color
description: Color picker that populates variables for passing to OBS and HTML objects
published: true
date: 2022-10-16T11:13:15.186Z
tags: 
editor: markdown
dateCreated: 2021-11-19T20:36:22.012Z
---

## Overview
Convert a selected color into a bank of variables that can then be passed to C# code, HTML objects, or any OBS source that is color-aware.

![pick-color.png](/pick-color.png)

## Configuration
### Color / OBS Color
The Color picker will give the standard pallet picker so you can chose by a slider or by entering raw RGB / HSL values

Once a color is chosen the `Color` box will be populated with the RGB Hex value and `OBS Color` will populate with the raw integer value OBS expects for ABGR it uses for its natively supported sources.

### Variable Name
Enter an alias for the resulting variables, outlined below. Don't use %'s in this field this will be done automatically.

## Variables
The following variables will be available after execution of this sub-action:

> In each of the following variables, replace `variableName` with the variable name you configured.
{.is-warning}

Name | Description
----:|:------------
`variableName.color.a` | The alpha value
`variableName.color.r` | The red value
`variableName.color.g` | The green value
`variableName.color.b` | The blue value
`variableName.html` | The html color code
`variableName.htmlalpha` | The html color code with alpha value
`variableName.obs` | The color as an OBS ABGR value

---

- [<i class="mdi mdi-chevron-left"></i>**Sub-Actions Reference *Go Back***](/en/Sub-Actions)  
- [<i class="mdi mdi-numeric primary--text"></i>**Get Random Number *Populate a variable with a random number***](/en/Sub-Actions/Get-Random-Number)
{.btn-grid .my-5}