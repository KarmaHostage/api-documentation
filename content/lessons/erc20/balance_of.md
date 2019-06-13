---
title: "Balance Of"
---

Fetch the balance of an address for a specific ERC20 Token. Balance returned contains the raw balance as well as the actual balance.

## Example Request

```javascript
curl -X GET \
  https://api.cinder.cloud/api/ethereum/erc20/0xB8c77482e45F1F44dE1745F52C74426C631bDD52/balance/0x3f5ce5fbfe3e9af3971dd833d26ba9b5c936f0be \
  -H 'Content-Type: application/json'
```

## Example Response

```json
{
    "balance": "3190230.996754",
    "rawBalance": "3190230996754360789793475"
}
```
