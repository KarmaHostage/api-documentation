---
title: "Listen for Transfers"
---

Listen for transfers for an ERC20 token. Watch out, this is using Server-Sent Events!

## Example Request

```javascript
curl -X GET \
  https://api.cinder.cloud/api/ethereum/erc20/0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359/transfer-events \
  -H 'Content-Type: application/json'
```

## Example Response Observable

```json
{
  "from" : "0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950",
  "to" : "0x04a487afd662c4f9deacc07a7b10cfb686b682a4",
  "amount": 405862294683723403964
}
```