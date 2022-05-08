---
slug: /sdk.erc20batchmintable.to
title: Erc20BatchMintable.to() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## Erc20BatchMintable.to() method

Mint Tokens To Many Wallets

**Signature:**

```typescript
to(args: TokenMintInput[]): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type                                          | Description |
| --------- | --------------------------------------------- | ----------- |
| args      | [TokenMintInput](./sdk.tokenmintinput.md)\[\] |             |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

## Remarks

Mint tokens to many wallets in one transaction.

## Example

```javascript
// Data of the tokens you want to mint
const data = [
  {
    toAddress: "{{wallet_address}}", // Address to mint tokens to
    amount: 0.2, // How many tokens to mint to specified address
  },
  {
    toAddress: "0x...",
    amount: 1.4,
  },
];

await contract.mintBatchTo(data);
```