---
description: >-
  The current NFT course token metadata is stored under ONGAESHI centralized
  database. The metadata recorded NFT information such as token ID, attributes
  and the on-loan progress and etc.
---

# View NFT Metadata

API Input: NFT Collection Address, Token ID

API Return: Metadata of the specific NFT Token

API to return all the metadata for the specific NFT token. The URL will be used by the URI inside the NFT tokenURI for fetching metadata. This is the main API to return the NFT metadata but would like to upgrade to the IPFS path in the future.

{% embed url="https://api-ongaeshi.xwin.com.my/docs/nft-mgmt#/nft/GetMetadata" %}

```json
{
  "nftCollectionAddress": "0xDe3E800D5Eba73c529707EB565d89fbD55Bc77D7",
  "tokenId": 1,
  "courseURI": "https://course/xxxxx/",
  "desc": "A up to 200 length of varchar description for the NFT collections",
  "attributes": [
    {
      "traitType": "duration",
      "traitValue": "6 months"
    }
  ],
  "onGoingLoan": {
    "talentId": "7fb2c6d6-1562-4819-a12f-e6aa824cd8b6",
    "completedAt": "2024-01-31T07:39:01.775Z",
    "status": "New",
    "onloanId": "cj9jc2e412o73lc25r4g"
  },
  "onLoanHistory": [
    {
      "talentId": "7fb2c6d6-1562-4819-a12f-e6aa824cd8b6",
      "completedAt": "2024-01-31T07:39:01.775Z",
      "status": "New",
      "onloanId": "cj9jc2e412o73lc25r4g"
    }
  ]
}
```
