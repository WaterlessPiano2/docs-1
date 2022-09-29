---
slug: /sdk.nftdrop.get
title: NFTDrop.get() method
hide_title: true
displayed_sidebar: solana
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## NFTDrop.get() method

Get the metadata for a specific NFT

**Signature:**

```typescript
get(nftAddress: string): Promise<NFTMetadata | undefined>;
```

## Parameters

| Parameter  | Type   | Description                        |
| ---------- | ------ | ---------------------------------- |
| nftAddress | string | the mint address of the NFT to get |

**Returns:**

Promise&lt;[NFTMetadata](./sdk.nftmetadata.md) \| undefined&gt;

the metadata of the NFT

## Example

```jsx
const mintAddress = "...";
const nft = await program.get(mintAddress);
```