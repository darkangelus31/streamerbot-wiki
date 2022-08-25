---
title: Raw (v5)
description: OBS raw is powerfull tool to do OBS things that you can't do in regular sub-actions.
published: false
date: 2022-08-25T05:56:10.764Z
tags: 
editor: markdown
dateCreated: 2022-08-20T18:39:46.278Z
---

> Because of the switch between OBS WebSocket *v4.9+*{.obs-version-badge} and *v5+*{.obs-version-badge}, we have decided to put the documentation in *v5+*{.obs-version-badge}
{.is-warning}
---
> Since there are quite a large number of possible requests that can be sent to OBS via obs-websocket, its not possible to have every single one, along with all the different options available, as a simple sub-action.
>
> OBS Raw, will let you take full control over sending data to OBS.
{.is-info}
# Result/Variables
To use variables in the JSON request, add the % variable surrounded by quotes, it must still be valid JSON to parse properly.  The variable will be auto-typed when it is parsed to be sent to OBS, so if the variable is a number, the resulting JSON will not have double quotes around the value.

When the OBS Raw is executed, result will be places in the argument stack for the action.

Since the result is returned in JSON, it will walk the entire tree, and add each value as a `obsRaw.<JSON Path>` for use.

A special `obsRaw._json` will also be added, which is the entire JSON as a string, this is mainly for use in C# where you can deserialize this into an object for easier access/traversal.

# Tabs
## Raw
The raw code is in `JSON` and you need to follow the list of [Requests](/en/Broadcasters/OBS/Requests), and put those request fields in the `requestData` object.

![obsraw-menu-raw-default.png](/broadcasters/obs/raw/raw/obsraw-menu-raw-default.png)

## Preview
In the preview you see your raw code visually.

![obsraw-menu-preview.png](/broadcasters/obs/raw/preview/obsraw-menu-preview.png)
## Result
When you have clicked on the `Test` button you will see all the Response Fields/Variables.

<small>The GetVersion request was used for this example.</small>
![obsraw-menu-result-request-getversion.png](/broadcasters/obs/raw/result/obsraw-menu-result-request-getversion.png)
## Options
Here you see one parameter you can change to if the `Results` can be used as variables, by default this is on.

![obsraw-menu-options.png](/broadcasters/obs/raw/options/obsraw-menu-options.png)
- [x] Add results to arguments

# Other
### Name
Give this a name to sort it between the other sub-action (for example you can use your request type).

### Variable Prefix
This will be in front of your variables when an action has ran.

### Format
Using this button your raw code will automatticly be JSON formatted.

### Test
This will test the raw code, but this won't run the action/sub-action in any way.

### Connection
You can change between obs connections, only advanced user will use this feauture.

### Ok
This will save and close your code menu.

### Cancel
This will undo what you just changed to the code and close the code menu.

***

### Format
```json
{
  "requestType": "request method",
  "requestData": { ... }
}
```

All the request fields can be found at the OBS raw Requests page
- [<i class="mdi mdi-frequently-asked-questions text--obs"></i>**OBS Raw Requests *Reference of all requests supported with OBS Raw***](/en/Broadcasters/OBS/Requests)
{.btn-grid .my-5}