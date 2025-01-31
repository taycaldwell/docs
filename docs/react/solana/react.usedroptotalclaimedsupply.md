---
slug: /solana/react.usedroptotalclaimedsupply
title: useDropTotalClaimedSupply() function
hide_title: true
displayed_sidebar: react
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## useDropTotalClaimedSupply() function

Get the total claimed supply of NFTs on an NFT Drop

## Example

```jsx
import {
  useProgram,
  useDropTotalClaimedSupply,
} from "@thirdweb-dev/react/solana";

export default function Component() {
  const { program } = useProgram("{{program_address}}");
  const { data: claimedSupply, isLoading } = useDropTotalClaimedSupply(program);

  return <p>{claimedSupply}</p>;
}
```

**Signature:**

```typescript
export declare function useDropTotalClaimedSupply(
  program: RequiredParam<NFTDrop>,
): import("@tanstack/react-query").UseQueryResult<number, unknown>;
```

## Parameters

| Parameter | Type                         | Description                                       |
| --------- | ---------------------------- | ------------------------------------------------- |
| program   | RequiredParam&lt;NFTDrop&gt; | The NFT Drop program to get the claimed supply on |

**Returns:**

import("@tanstack/react-query").UseQueryResult&lt;number, unknown&gt;
