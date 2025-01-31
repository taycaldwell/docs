---
slug: /react.usemultiwrap
title: useMultiwrap() function
hide_title: true
displayed_sidebar: react
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## useMultiwrap() function

> Warning: This API is now obsolete.
>
> This hook is deprecated and will be removed in a future major version. You should use instead.
>
> ```diff
> - const multiwrap = useMultiwrap("0x1234...");
> + const multiwrap = useContract("0x1234...", "multiwrap").contract;
> ```

Hook for getting an instance of an `Multiwrap` contract. This contract is an ERC721 in which you can wrap ERC721, ERC1155 and ERC20 tokens.

## Example

```javascript
import { useContract } from '@thirdweb-dev/react'

export default function Component() {
  const { contract } = useContract("<YOUR-CONTRACT-ADDRESS>", "multiwrap")

  // Now you can use the multiwrap contract in the rest of the component

  // For example, this function will let the connected wallet wrap tokens
  async function wrap(tokensToWrap, wrappedNFTMetadata) {
    await contract.wrap(tokensToWrap, wrappedNFTMetadata)
  }

  ...
}
```

**Signature:**

```typescript
export declare function useMultiwrap(
  contractAddress: RequiredParam<string>,
): import("@thirdweb-dev/sdk").Multiwrap | undefined;
```

## Parameters

| Parameter       | Type                                                    | Description                                                             |
| --------------- | ------------------------------------------------------- | ----------------------------------------------------------------------- |
| contractAddress | [RequiredParam](./react.requiredparam.md)&lt;string&gt; | the address of the Multiwrap contract, found in your thirdweb dashboard |

**Returns:**

import("@thirdweb-dev/sdk").Multiwrap \| undefined
