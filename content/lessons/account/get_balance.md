---
title: "Get Balance"
---

Get the balance of an Ethereum account. The result is the full balance in WEI.

## Request

```javascript
curl -X GET \
  -H 'Content-Type: application/json' \
  https://api.cinder.cloud/api/ethereum/address/0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2/balance
  
```

## Example Response Observable

```json
{
    "balance": "179.71975181", 
    "rawBalance": "179719751810239407373"
}
```

