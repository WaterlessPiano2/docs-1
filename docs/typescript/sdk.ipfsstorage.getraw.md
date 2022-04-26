---
slug: /sdk.ipfsstorage.getraw
title: IpfsStorage.getRaw() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->


## IpfsStorage.getRaw() method

Fetches data from storage. This method does not make any assumptions on the retrieved data format

**Signature:**

```typescript
getRaw(hash: string): Promise<string>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  hash | string | The Hash of the file to fetch |

**Returns:**

Promise&lt;string&gt;

- The data, if found.