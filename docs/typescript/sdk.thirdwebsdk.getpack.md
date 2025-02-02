---
slug: /sdk.thirdwebsdk.getpack
title: ThirdwebSDK.getPack() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ThirdwebSDK.getPack() method

> Warning: This API is now obsolete.
>
> This method is deprecated and will be removed in a future major version. You should use instead.
>
> ```diff
> - const pack = await sdk.getPack("0x1234...");
> + const pack = await sdk.getContract("0x1234...", "pack");
> ```

Get an instance of a Pack contract

**Signature:**

```typescript
getPack(contractAddress: string): Promise<import("..").Pack>;
```

## Parameters

| Parameter       | Type   | Description                          |
| --------------- | ------ | ------------------------------------ |
| contractAddress | string | the address of the deployed contract |

**Returns:**

Promise&lt;import("..").[Pack](./sdk.pack.md)&gt;
