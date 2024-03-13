# Loan Details

API Input: UserID

API Return: NFT on-loan detail

This API returns NFT on-loan by user ID.&#x20;

For talents, this can be a way to see if they have been accepted to borrow the NFT.

For sponsors, this can be useful for the sponsors to log in to check their NFT status. This includes the pending request that needs approval from the sponsor.

## Talent:&#x20;

{% embed url="https://api-ongaeshi.xwin.com.my/docs/nft-mgmt#/nft-rental/getOnLoanByTalent" %}

## Sponsor:&#x20;

{% embed url="https://api-ongaeshi.xwin.com.my/docs/nft-mgmt#/nft-rental/getOnLoanBySponsor" %}

```json
[
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
]
```
