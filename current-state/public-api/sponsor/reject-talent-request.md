---
description: API that sponsor will use to reject the lending request by the talent
---

# Reject Talent Request

API Input: OnLoanID

API Return: On Loan Status Detail

API for the sponsor to reject the lend request made by the talent off-chain. At this point, it doesn't update the blockchain data.

{% embed url="https://api-ongaeshi.xwin.com.my/docs/nft-mgmt#/nft-rental/generalRejectLendRequest" %}

```json
{
  "id": "cgn42mbnuqpepeblrq50",
  "tokenId": 1,
  "repairCost": 1,
  "nftCollectionAddress": "0xDe3E800D5Eba73c529707EB565d89fbD55Bc77D7",
  "status": "Reject",
  "talentId": "8ddeac1f-b0f0-4100-8089-358f29b6c388",
  "coachId": "f8c69e48-3dfc-4ab5-b0fb-70216cdeb698",
  "sponsorId": "eaa04823-4978-4934-8dca-8c836d06b10c"
}
```
