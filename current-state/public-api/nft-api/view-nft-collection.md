# View NFT Collection

API Input: None

Return: All the NFT Collection addresses (NFT Category)

NFT collection is created without any owner until it is minted. Once the sponsor mints the NFT collection the ownership of the NFT collection is set to the owner. This can be useful when users want to see all the NFT collections offered and use the next GetNFTCollectionByAddress to get more details on the NFT.

{% embed url="https://api-ongaeshi.xwin.com.my/docs/nft-mgmt#/nft-collections/GetNFTCollections" %}

```json
{
  "pagination": {
    "totalCount": 1,
    "totalPage": 1,
    "currentPage": 1,
    "prevPage": null,
    "nextPage": null,
    "pageSize": 10
  },
  "data": [
    {
      "id": "cgn42mbnuqpepeblrq50",
      "createdAt": "2024-01-31T07:38:15.529Z",
      "updatedAt": "2024-01-31T07:38:15.529Z",
      "nftCollectionAddress": "0xDe3E800D5Eba73c529707EB565d89fbD55Bc77D7",
      "tokenURI": "https://igs/getmetadata/",
      "courseURI": "https://course/xxxxx/",
      "price": 1,
      "treasuryFee": 1,
      "treasury": "0xddbcdec9c996615b9d06bb7c9ce1083d1255c860",
      "maxSupply": 1,
      "name": "UI/UX Workshop",
      "symbol": "UIUX",
      "desc": "A up to 500 length of varchar description for the NFT collections",
      "transactionHash": [
        {
          "type": "TokenMintEvent",
          "value": "0x3d6257de1e88bf33b7e230b0e041e1dd234645db55345cfd30a4d2b5d553f3c8"
        }
      ],
      "attributes": [
        {
          "traitType": "duration",
          "traitValue": "6 months"
        }
      ],
      "teacherShares": [
        {
          "teacher": "0x3C44CdDdB6a900fa2b585dd299e03d12FA4293BC",
          "shares": 10000
        }
      ]
    }
  ]
}
```
