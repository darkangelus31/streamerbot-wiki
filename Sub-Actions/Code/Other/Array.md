---
title: Array
description: 
published: true
date: 2022-11-01T19:23:42.567Z
tags: 
editor: markdown
dateCreated: 2022-07-17T14:26:01.568Z
---

## Looks
### Example 1
Here you see 3 nested objects inside of this array{.subtitle}


### Tab {.tabset}
#### One line
```json
[{"name":"nested object"}, {"name":"nested object"}, {"name":"nested object"}]
```
#### More lines
```json
[
   {
      "name":"nested object"
   },
   {
      "name":"nested object"
   },
   {
      "name":"nested object"
   }
]
```

### Example 2
Here you see an array with 3 integers{.subtitle}
### Tab {.tabset}
#### One line
```json
[10, 20, 30]
```
#### More lines
```json
[
   10,
   20,
   30
]
```
### Example 3
Here you see an array with a nested object and a nested array with 3 integers, 1 boolean and 1 string{.subtitle}
### Tab {.tabset}
#### One line
```json
[{"name":"nested object"},[10, 20, 30, false, "nested array"]]
```
#### More lines
```json
[
   {
      "name":"nested object"
   },
   [
      10,
      20,
      30,
      false,
      "nested array"
   ]
]
```
### Example 4
### Tab {.tabset}
#### OBS ReorderSceneItems Request
```json
{
"requestType":  "ReorderSceneItems",
	"requestData": {	
"scene": "sceneName",
"items": [{"name":"firstSource"},{"name":"secondSource"}]
	}
}
```
#### One line
```json
[{"name":"firstSource"},{"name":"secondSource"}]
```
#### More lines
```json
[
  {
    "name":"firstSource"
  },
  {
    "name":"secondSource"
  }
]
```
## Explanation
A JSON array contains elements separated by comma's, The JSON array is surrounded by square brackets <span class="mdi mdi-code-array primary--text"></span>.

### Break Down

Elements: An element is something from the list of <a class="mdi mdi-sprinkler-variant primary--text" href="/en/Sub-Actions/Code"> Data Types</a>