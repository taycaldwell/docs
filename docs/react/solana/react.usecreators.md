---
slug: /solana/react.usecreators
title: useCreators() function
hide_title: true
displayed_sidebar: react
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## useCreators() function

Get the creators for an NFT program

## Example

```jsx
import { useProgram, useCreators } from "@thirdweb-dev/react/solana";

export default function Component() {
  const { program } = useProgram("{{program_address}}");
  const { data: creators, isLoading } = useCreators(program);

  return <pre>{JSON.stringify(creators)}</pre>;
}
```

**Signature:**

```typescript
export declare function useCreators(
  program: RequiredParam<NFTCollection | NFTDrop>,
): import("@tanstack/react-query").UseQueryResult<
  import("@thirdweb-dev/sdk/solana").CreatorOutput[],
  unknown
>;
```

## Parameters

| Parameter | Type                                              | Description                             |
| --------- | ------------------------------------------------- | --------------------------------------- |
| program   | RequiredParam&lt;NFTCollection &#124; NFTDrop&gt; | The NFT program to get the creators for |

**Returns:**

import("@tanstack/react-query").UseQueryResult&lt;import("@thirdweb-dev/sdk/solana").CreatorOutput\[\], unknown&gt;
