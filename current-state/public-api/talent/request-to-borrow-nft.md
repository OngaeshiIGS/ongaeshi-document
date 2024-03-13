---
description: >-
  This is off-chain request that talent will ask the sponsor for the NFT lending
  purpose.
---

# Request to Borrow NFT

API Input: NFT Collection Address, Token ID

API Return: OnLoan Status data

API for logged in talent to request to borrow the NFT. Talent credential uuid to be used as talent ID. At this point, no data is to be written in the smart contract yet. This off-chain request is sent into the queue for approval or rejection.

{% embed url="https://api-ongaeshi.xwin.com.my/docs/nft-mgmt#/nft-rental/lendRequest" %}

Example of Return:

```json
{
  "id": "cgn42mbnuqpepeblrq50",
  "createdAt": "2024-01-31T07:36:58.031Z",
  "updatedAt": "2024-01-31T07:36:58.031Z",
  "nftCollectionAddress": "0xDe3E800D5Eba73c529707EB565d89fbD55Bc77D7",
  "tokenId": 1,
  "coachId": "7fb2c6d6-1562-4819-a12f-e6aa824cd8b6",
  "talentId": "7fb2c6d6-1562-4819-a12f-e6aa824cd8b6",
  "sponsorId": "7fb2c6d6-1562-4819-a12f-e6aa824cd8b6",
  "transactionHash": [
    {
      "type": "TokenMintEvent",
      "value": "0x3d6257de1e88bf33b7e230b0e041e1dd234645db55345cfd30a4d2b5d553f3c8"
    }
  ],
  "status": "New"
}
```
