---
description: API that sponsor will use to approve the lending request by the talent
---

# Accept Talent Request

API Input: OnLoanID

API Return: On Loan Status Detail

API for sponsors to approve the NFT lend request made by the talent. This will update the NFT status in the blockchain.

{% embed url="https://api-ongaeshi.xwin.com.my/docs/nft-mgmt#/nft-rental/generalAssignOnLoan" %}

```json
{
  "id": "cgn42mbnuqpepeblrq50",
  "tokenId": 1,
  "repairCost": 1,
  "nftCollectionAddress": "0xDe3E800D5Eba73c529707EB565d89fbD55Bc77D7",
  "status": "New",
  "talentId": "8ddeac1f-b0f0-4100-8089-358f29b6c388",
  "coachId": "f8c69e48-3dfc-4ab5-b0fb-70216cdeb698",
  "sponsorId": "eaa04823-4978-4934-8dca-8c836d06b10c"
}
```
