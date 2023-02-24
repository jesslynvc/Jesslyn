# KDP articles - Asynchronous processing

https://bozuman.cybozu.com/k/22682/show#record=393

Index
- [Overview](##overview)
- Method 1: CallBacks
- Method 2: Promise
- Method 3: async/await

## Overview
This article introduces how to use kintone.api() to run kintone REST API.

## CallBacks
When you use kintone.api() to execute kintone REST API, specify the callback function when the fourth argument succeeds.
In API documentation it is referred to as "CallBacks".

```
kintone.api (API path, method, request parameter, callback function when successful, callback function when failed)
```