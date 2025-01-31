---
slug: /sdk.thirdwebsdk.getprogramwithidl
title: ThirdwebSDK.getProgramWithIdl() method
hide_title: true
displayed_sidebar: solana
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ThirdwebSDK.getProgramWithIdl() method

Get an SDK interface for a deployed program

**Signature:**

```typescript
getProgramWithIdl(address: string, idl: Idl): Promise<Program>;
```

## Parameters

| Parameter | Type   | Description            |
| --------- | ------ | ---------------------- |
| address   | string | Address of the program |
| idl       | Idl    | The IDL of the program |

**Returns:**

Promise&lt;[Program](./sdk.program.md)&gt;

SDK interface for the program

## Example

```jsx
import idl from "path/to/idl.json";

// Alternatively, you can pass in your own IDL
const program = await sdk.getProgramWithIdl(address, idl);
```
