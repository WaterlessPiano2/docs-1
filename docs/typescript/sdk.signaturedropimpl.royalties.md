---
slug: /sdk.signaturedropimpl.royalties
title: SignatureDropImpl.royalties property
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## SignatureDropImpl.royalties property

Configure royalties

## Example

```javascript
// royalties on the whole contract
contract.royalties.setDefaultRoyaltyInfo({
  seller_fee_basis_points: 100, // 1%
  fee_recipient: "0x...",
});
// override royalty for a particular token
contract.royalties.setTokenRoyaltyInfo(tokenId, {
  seller_fee_basis_points: 500, // 5%
  fee_recipient: "0x...",
});
```

**Signature:**

```typescript
royalties: ContractRoyalty<
  SignatureDropContract,
  typeof DropErc721ContractSchema
>;
```

## Remarks

Set your own royalties for the entire contract or per token